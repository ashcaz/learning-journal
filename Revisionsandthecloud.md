# Revisions and the cloud

**Version control (VCS)**

- Version control is a system that records changes and allows you to go back to a previous versions of that file or files

**Local Version Control**
 - lives on your hard disk/computer
 
 **Distributed Version Control (DVCS)**
 - uses multiple serves to house changes and versions and eliminates single server point of failure

**What is Git?**
* version control system
* lets multiple developers work on same code
* history of changes
* ability to view, apple, and remove those changes
* keep all project files in one repository

Git keeps track of what the file looked like at different points in time

- you use git to take snapshots of your code at points and time
- git keeps a history of what those snapshots are
- git has a special label called HEAD, which means "You Are Here"

**What is GitHub?**
- a way to share code with others
- an online place to store code

**git + GitHub = Awesome!!!**
- allows everyone to work on code then sync it up online

**What is a Repository?**

- A repo is a collection of files that you've told git to pay attention to
one project one repo

### Git and github with terminal
 
 **Git  Workflow**
 
 **ACP** : add commit push
 
 **Terminal Commands**
- git add <filename> : add before committing allows for tracking of file
- git fetch : hey go look at the repo and tell me what you see 
  - can open up and show changes
- git status : analyzes the differences between GitHub and whats on your computer
- git push origin master : pushes changes on computer to github master
- git commit -m " " commit with a message
- git pull : fetch and merge in one
 
 **Clone a repo on GitHub with terminal to local machine**
 
- open terminal and verify you are at root level
- create new directory mkdir ________
- navigate to directory cd _________
-create new directory within mkdir_______
- navigate to directory cd ________
- goto repo on github and hit clone then copy url
- in terminal type git clone URL hit enter
- in terminal type git remote -v to verify
- in terminal type git status to verify if you have the current version

**Using repo locally in VS code with terminal**

- type code . to launch VS code with current repo
- make changes in vs code if needed
- type git add or git commit-a to update file with changes
- type git reset to unstage or undo changes
- type git commit -m “reason for change” to add message to commit change
- type git push origin master to upload/publish to github
- type git fetch to compare origin/master file if changes have been made on github
- type git pull origin/master to download changes made on GitHub to local file.
 
 [Back to Home Page](https://ashcaz.github.io/learning-journal/)
