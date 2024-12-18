# How-to-Learn-Git

## Resources for those new to GitHub and Git with annotations from a relatively new Git/GitHub user

### How I would go about learning Git if I knew everything I know now at the beginning 
### (Resources That I Have Used, in the Order I Encountered Them)
One of the first things I encountered, perhaps by luck or through research, was that GitHub offers Pro for free to students. Thus, if you are a student like me, I would encourage you to verify your student identity to unlock free, powerful resources such as Copilot and much more. You can find all the offers in the GitHub Student Developer Pack in the link below. You can also sign up for the Student Pro Offer easily after clicking on that link.
* https://education.github.com/pack#github-copilot

The very first tutorial that I used from the GitHub Student Developer Pack was Introduction to GitHub. This tutorial was informative and easy to follow. It only takes about 15-20 minutes. However, this only covers how to do version control on Github, and not with Git. What I mean is this tutorial covers features on the GitHub site, and not remotely changing with Git.
* https://github.com/skills/introduction-to-github

The second tutorial that I did was how to create a GitHub Page. I thought that it would be interesting to do, but I ended up realizing that it was too hard to implement. I wouldn't recommend this tutorial but if you are interested in creating a blog/page of a repository, this is a basic guide to that. 
* https://github.com/skills/github-pages

I use VSCode Interpreter, and I wanted to learn how to use Git in VSCode. I first noticed that VSCode allows one to link their GitHub account with the local VSCode interpreter, allowing for an easy connection between code and GitHub, so I did that. I found out how to do this on my own, but if you need a guide I will put it in the first bullet point below. Afterwards, I downloaded Git for Windows, to be able to exploit Git (link to Git in the second bullet below). Now, I was ready to learn how to use Git. The video that I found most helpful was under VSCode's YouTube channel, which was "Official Beginner's Guide to GitHub Using VSCode." It helped a lot with the basics of how to use Git source control with VSCode, but you need to practice and review the video a few times to fully understand everything about committing, branching, merging, and push/pulling. I have put that video below as well. I would recommend all of these steps (some are mandatory, like installing Git!).
* https://www.youtube.com/watch?v=uqZwcUTVew8
* https://git-scm.com/downloads
* https://www.youtube.com/watch?v=i_23KUAEtUM&t=254s&pp=ygUTZ2l0aHViIHdpdGggdnMgY29kZQ%3D%3D

On a whim, after some early commits and repository creations, I wanted to upgrade my profile landing page. I found this short video (in bullet below) that explains how to make some simple and cool visuals with little to no effort. I did something very basic and you can check out my profile (if you haven't already!) to see what I mean. If you like it, I would highly recommend it!
* https://www.youtube.com/watch?v=DWFs6aqknqw

For the first stretch goal that I was assigned in my class, I needed to explore the difference between functional code, and professionally-ready code. Through my research and actions, I had to implement Git/GitHub and do research on both. I noted my findings and actions in the document that I wrote below. I would recommend documenting things that you have learned and sharing them with others to get feedback on your understanding and improve your technical writing abilities.
* https://docs.google.com/document/d/1kISeX1kLAWPYo4WMF4C1HkhNQaWgN5VVfX4P5wZZieo/edit?usp=sharing

I would also encourage working with others on code as early as possible. What I mean is to join a group project and create a group repository so that you can implement your knowledge about branches, merging, and push/pulling. This way, you will have these concepts deeply reinforced. I haven't done this yet, but I did contribute to one of my classmate's repositories, and through that, I could practice branches, merging, and push/pulling on a small scale.

One of the most recent things that I have learned to do on GitHub is how to write a useful README file. These are arguably the most important files in a GitHub repository as they inform a prospective reader about what the repository is about, what is being worked on, what known issues there might be, and how one could contribute. For me, some of these additions to the README file are overkill, but I would say that learning about formatting, adding images, and simple things like how to bullet and space correctly is vital to creating a functional README file. Some resources that I found and would recommend are below:
* https://www.youtube.com/watch?v=E6NO0rgFub4
* https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github
* https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#paragraphs

As of now, the final piece of material that I have been looking at is how to use Git outside of the VSCode interpreter i.e. through the command prompt/Git Bash. The repository that I am using is created by my teacher Dr. Zufelt and I will share my notes below. The repository is very informative and I have been learning a lot so far.

Overall, I would characterize my experience with Git and GitHub as fulfilling and challenging. While I still have initial difficulties with version control, it is fun to learn about the ways that I can organize files and share and collaborate with others. I feel like I am starting to understand how to use Git and GitHub in meaningful manners.

### My Notes On a Follow-Through of Dr. Zufelt's Guide to Git
My teacher in CSC 471: Cryptography Dr. Zufelt has given me a bunch of videos, resources, and exercises to learn how to use Git. I have forked the repository that contains the material that I am following: https://github.com/aaron-h6665/resources_for_students.git. There is also info on Web Dev if you are interested but I will not be covering that.

1. The Command Line <br /> <br />
I am using Git Bash. Here are some basic commands that one can use in the command line. They are useful in navigating the folders on your computer, creating new folders and files, and copying, deleting, moving, and listing folders and files. You could do all this manipulation of folders manually, but honestly it's valuable to learn all these commands. 
   * cd {directory} - Change to the directory to "{directory}" (make sure that this directory nested in your current directory)
   * cd .. - Change to Parent Directory
   * code {file} - Create a file specified by "{file}" i.e. code hello.py creates hello.py
   * cp  - Copy 
   * rm {file} - Remove "{file}"
   * mkdir {name} - Make Directory called "{name}"
   * mv - Move File
   * ls - List Files/Folders in Working Directory
   * pwd - Print Working Directory

2. Commits <br /> <br />
Consider the normal saving capabilities of a file. If you want to return to a previous version, you may be unable to do that as you have overwritten the previous versions of the file with the current version. However, Git commits get around this (like a snapshot in time). First, you would initialize a folder to become a Git repository through "git init." Then you would use "git add" to track the file changes. Lastly, you would use "git commit -m" to commit those changes locally.
   * git init - Initialize a Folder as a Git Repository
   * git add - Turn Untracked Files to Tracked (Changes can be Committed)
   * git commit -m "{commit description}"- Commit Changes under "{commit description}" i.e. git commit -m "first commit" if it is your first commit
   * git checkout {branch}- the basic mechanism for moving around in the commit tree, moving your focus (HEAD) to the specified {branch}.
   * git log - A Log of Commits (Author, Date, Name of Commit)
   * git status - shows the status of your repository

3. Vim <br /> <br />
When you type git commit without the "-m" you will enter the code editor of Vim which is built into the command prompt. Vim is high-powered but very complex.
We don't need to use it for now. To escape, and make a commit, type ":wq" (write quit).

4. Exercise: "Now that you've seen the basics of the command line and git, I want you to make a repository that has exactly 4 commits in it." <br /> <br />
I approached this problem by changing directories (cd) until I reached a desired directory and then making a new one using mkdir. Then, I used "git init" to initialize the new directory as a Git Repository. Next, I created a new Python file called test using "code test.py." This should open a new file in your interpreter. In my case, my Visual Studio Code opened up to a blank file called "test.py." Then make a basic edit to the file. I just added something simple like "10+10." Right now the file is untracked, so we should make the file tracked (changes can be committed) by using "git add test.py." Now we can make our first commit by using "git commit -m 'first commit'". First commit done. To reach four commits, we would just make three more edits and commit each time (remember to use "git add" each time). That's how we can reach exactly 4 commits to the repository. You can check how many commits you are at using "git log."

![Alt Text](git_log_example)

5. Git: Branches, Merges, and Checking Out <br /> <br />
Branches and Merges are important features of Git. They allow us to work on two separate portions of a project at the same time and ultimately merge them together. The "git checkout" command allows us to switch our HEAD (which points to which branch we are on) between branches.
   * git checkout -b feature - "-b" stands for making a branch. Switches to the "feature" branch.
   * HEAD (points to) -> feature (now instead of master)
   * It is important to remember that when you branch two branches together, there is a "giver" and a "receiver."
   * git merge {master} - Merge two branches together.
     * sometimes when you use git merge there will be a conflict, but look further down to number 8 to see how to resolve this issue if you need help with that
   * git checkout - the basic mechanism for moving around in the commit tree, moving your focus (HEAD) to the specified commit.

6. Exercise -- Now, I'd like for you to make a particular git tree. (Meaning: make a git repository, and create commits such that the commit tree looks like as below.) 
![Git Diamond](git_diamond.png)
* How can you prove that this correct? _(Hint: it requires multiple uses of `git log`.)_

I will again explain my approach. First, we need to have an initial commit. Then we create a new branch "feature" using "git checkout -b feature." This will also switch to the "feature" branch. Now, we switch back to the "master" branch using "git checkout master." We add our second and third commits to the master branch. Then we switch our "HEAD" to feature. Notice that the feature branch does not have the second or third commits.

![Alt_Text](feature_no_second_or_third_commit.png)

Now, we should make our fourth commit, which will only appear on the feature branch. Switch once again back to master. Notice that the master branch does not have the fourth commit.

![Alt_Text](master_no_fourth_commit.png)

Now we use "git merge feature" to merge the "feature" branch with "master" and this will effectively be our fifth commit, thus completing the diagram and task above. Notice where the "HEAD" points in the screenshot.

![Alt_Text](exercise_2_final.png)

7. [The Git Parable](https://tom.preston-werner.com/2009/05/19/the-git-parable.html) Reading
* a short, simple story that teaches or explains an idea
* I'm not going to lie, I didn't completely read the whole story in detail. But from what I did read, it has some nice analogies that would help a beginner better understand the workings behind Git, specifically with things such as commits, branches, merging, and more.

8. Merge Conflicts
   * less - shows the conflicts on the Git Bash/Command Prompt
   * git branch - shows all of the branches
   * git branch -d - locally delete a branch
   * git branch -D - force delete a branch
   * If you have a conflict you have to go into the interpreter to manually tweak the code, and then add and commit those changes. The merge will occur naturally (provided you have already tried to merge the files and the conflict appears).
  
9. Git Time Travel
  * git checkout {unique commit number} - moves to the specified commit

This will end up generating a text that says "you are in 'detached HEAD' state." 'Detached HEAD' means it isn't pointed at a branch, it is pointed at a commit. But this isn't so good because we don't have a branch associated. So all we have to do is to create a new branch using "git checkout -b {new_branch_name}" at this point and we are all good.

10. **Exercise** -- First, I'd like you to create a simple repository that has this git tree:
  ![Time Travel Part 1](Git_Time_Travel_1.png)  
  Then, I'd like you to turn that respository into the following one, via time travel:
  ![Time Travel Part 2](Git_Time_Travel_2.png)

Here, we do our first three commits. 
![Time Travel](master.png)

Then, we use the 'detached HEAD method' to go to the second commit. Now we create the "bug-fix" branch using "git checkout -b bug-fix" and finally we add the fourth commit (which is a "bug-fix").

![Time Travel](bug_fix.png)

11. Git Remote Repository
A Remote Repository is a repository that is not on your local device. Here are some commands that will help you "connect" your local device with the remote repository using cloning, push/pulling, and remoting.
  * git remote add {origin} {https link to GitHub Repo} - connects the remote repository to your local device
  * git remote - checks the name of the repo???
  * git remote -v - shows the name and fetch, push links
  * git push {origin} {name of branch} - pushes local code changes to the remote repository
  * You NEVER want to have Git Repositories inside of Git Repositories
  * git clone {https link to GitHub Repo} - clone a remote repository onto your local device
  * cat - current local version

So this video teaches us how to push local code to a remote repository and how to clone a remote repository onto a local device.

12. Git Pushing Happens with Branches, not Trees
* Basically, this is just saying you have to push branch by branch, and if for example, you are working on branch "master" but type "git push origin feature" where "feature" is a different branch, it won't work quite well. Just be careful with the branches that you are working with when pushing.

13. Exercise -- I want you now to practice a bunch with remotes:
init versus clone: You should make a git repository on your computer, create a remote for it (after having made it on your computer), and push code up to it. You should also make a repository on GitHub, clone it down, and figure out the difference. When would one method make more sense than another?
pushing: Make some changes to your code, and push up new changes. Verify that your remote repository is up to date with the local one afterward (and wasn't before!)
pulling: In order to practice pulling, we need to be a little bit clever. I want you to practice having the remote and local repositories being in different states, and then fixing it. Please create two repositories: one in which the local repository is "ahead" of the remote repository, and one in which the local branch is "behind" the remote repository. Then fix each one by pushing or pulling as appropriate (and confirm that they're now in sync). In thinking about that final point, you might be confused. How could you possibly have a remote branch that's ahead of your local branch if you're the only person editing the repository? Here are two ways you could set that up:
You can edit files directly on GitHub: what effect does that have?
You could have a local repository which you've cloned down to a totally different, second folder on your computer, which is purposefully going to be "old", then using the main (local) repository, you push up some new code. Now, the remote is ahead of the "old" version.

When you edit files directly on GitHub, those edits will only effect the files on GitHub. You will need to clone everything again to get stuff back. 

14. Forking and Pulling
* forking means when you go onto GitHub and you copy a repository that someone else owns and basically creates a copy that is now your own repository.
* origin - your repository; upstream - the other person's repository
* you can push and pull from origin, you can only pull from upstream
* pull request is when you request the other person to pull your version into their code.

15. Git Implementation
A few commands that allow for the pulling of someone else's code to your local device.
* git remote add upstream {link to other person's repo} - add upstream (the other person's repository) so that you can pull from there later on if somebody else made a new change
* git pull upstream master - pulls from the upstream to the master branch
  
16. Bug detection and real pull request.

[Finding and Fixing a scikit-learn bug](https://www.youtube.com/watch?v=1kA7oD7ftsM&t=88s) 
* Very cool video about contributing to the Open Source sci-kit learn

17. Exercise -- OH NO! I made a typo in this git repository. Can you help me fix it? Please submit a pull request.
* Just follow the video in 15 or 16 and you should be good to go!
