# GitTourneyI

Tournament of Git Merges

Note: main (master) branch cannot be pushed to. Make sure to follow the steps when you enter the tournment:

1) Clone the repo
2) Create your own branch: git checkout -b "my git username"
3) Create a directory for your entry: mkdir "my git username"
4) Go into your directory: cd "my git username"
5) Create your entry: nano "my entry".txt
6) Copy/paste your entry, save and quit
7) Add your new file to be tracked by git: git add "my entry".txt
8) Commit your file to your local repo: git commit -m "My entry rocks!"
9) Push your new branch up to the origin: git push
    * now, copy & paste the command from the error kicked out by git
    * You might get an extra special error because you didn't create a new branch and pushed to main. 
      - It'll include this in the error:  ! [remote rejected] main -> main (protected branch hook declined)
      - Go back to 2, but you might need to run 'git stash' and start over some.
10) Refresh the web interface to check that your new branch and file is there
11) Run 'git pull' to snag all those other branches just created by others

12) Look at the bracket to see which branch you need to merge with
  * refresh until it shows up or we decide they're not active
 12a) Create a merge request with that other branch to push your entry into their branch
 12b) Accept their merge request to merge into yours as well
 12c) Do a quick discussion on Zoom to decide which branch should 'win' your round and let Crandall know so he can update the bracket

13) Stick together with your merged branchmate for the next round
 13a) Run 'git pull' every so often to pick up the various merges
 13b) Also, refresh the website to show the growing repo commit graph
14) Check bracket for which branch should be merged with next

15) Repeat until the class is down to one branch

16) The "winner" should make a merge request with main for approval by Crandall
