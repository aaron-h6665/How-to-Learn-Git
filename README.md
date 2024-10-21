# How-to-Learn-Git

## Resources for those new to GitHub and Git with annotations from a relatively new Git/GitHub user

1. The Command Line
I am using Git Bash. Here are some basic commands that one can use in the command line.
  * cd - Change Directory
  * cd .. - Change to Parent Directory
  * code - Create File
  * cp - Copy
  * rm - Remove
  * mkdir - Make Directory
  * mv - Move File
  * ls - List Files/Folders in Working Directory
  * pwd - Print Working Directory

2. Commits
Consider the normal saving capabilities of a file. If you want to return to a previous version, you may be unable to do that as you have overwritten the file. However, Git commits get around this (like a snapshot in time).
   * git init - Initialize a Folder as a Git Repository
   * git add - Turn Untracked Files to Tracked (Changes can be Committed)
   * git commit -m - Commit Changes
   * git checkout - 
   * git log - A Log of Commits (Author, Date, Name of Commit)

3. Vim
When you type git commit without the "-m" you will enter the code editor of Vim which is built into the command prompt. Vim is high-powered, but very complex.
We don't need to use it for now. To escape, and make a commit, type ":wq" (write quit).

4. Git: Branches, Merges, and Checking Out
   * git checkout -b feature - "-b" stands for making a branch. Switches to the "feature" branch.
   * HEAD -> feature
   * Important that you branch two branches together, there is a "giver" and a "receiver."
   * git merge - Merge two branches together
