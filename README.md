# How-to-Learn-Git

## Resources for those new to GitHub and Git with annotations from a relatively new Git/GitHub user

### Resources That I Have Used, in the Order I Encountered Them
The very first tutorial that I used was this Introduction to Github that teaches you the basics.
* https://github.com/skills/introduction-to-github

I wouldn't recommend this tutorial but if you are interested in creating a blog/page of a repository, this is a basic guide to that.
* https://github.com/skills/github-pages

Official Beginner's Guide to GitHub Using VSCode:
* https://www.youtube.com/watch?v=i_23KUAEtUM&t=254s&pp=ygUTZ2l0aHViIHdpdGggdnMgY29kZQ%3D%3D

Level Up Your GitHub Profile:
* https://www.youtube.com/watch?v=DWFs6aqknqw

How to Write a Useful README File:
* https://www.youtube.com/watch?v=E6NO0rgFub4

How to Add Images to README:
* https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github

### My Notes On a Follow Through of Dr. Zufelt's Guide to Git
My teacher in CSC 471: Cryptography Dr. Zufelt has given me a bunch of videos, resources, and exercises to learn how to use Git. I have forked the repository that contains the material that I am following: https://github.com/aaron-h6665/resources_for_students.git. There is also info on Web Dev if you are interested but I will not be covering that.

1. The Command Line <br /> <br />
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

2. Commits <br /> <br />
Consider the normal saving capabilities of a file. If you want to return to a previous version, you may be unable to do that as you have overwritten the file. However, Git commits get around this (like a snapshot in time).
   * git init - Initialize a Folder as a Git Repository
   * git add - Turn Untracked Files to Tracked (Changes can be Committed)
   * git commit -m - Commit Changes
   * git checkout - 
   * git log - A Log of Commits (Author, Date, Name of Commit)

3. Vim <br /> <br />
When you type git commit without the "-m" you will enter the code editor of Vim which is built into the command prompt. Vim is high-powered, but very complex.
We don't need to use it for now. To escape, and make a commit, type ":wq" (write quit).

4. Git: Branches, Merges, and Checking Out <br /> <br />
Branches and Merges are important features of Git. They allow us to work on two separate portions of a project at the same time and ultimately merge them together. Checkout allows us to switch our HEAD between branches.
   * git checkout -b feature - "-b" stands for making a branch. Switches to the "feature" branch.
   * HEAD -> feature
   * Important that you branch two branches together, there is a "giver" and a "receiver."
   * git merge - Merge two branches together
