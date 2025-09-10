* What is the difference between tracked and untracked files in Git?
* After cloning a repository, why are files initially “tracked but unmodified”?
* What command is used to clone a GitHub repository to your local machine?
* What happens after running `git init` in a directory?
* Explain the difference between **modified files** and ​**staged files**​.
* Why is the **staging area** important?
* Which command moves changes from working directory → staging area?
* Which command creates a snapshot of staged changes into the history?
* Give an example scenario where staging allows you to make a more meaningful commit.
* What does git config do for you, How you can use git config to help you with different projects?

#### Commands

Practice these commands and record what happens when you type these commands

1. git --version
2. git config first check if not setup then set your config
   1. git config --global user.name
   2. git config --global user.email
   3. git config  user.name
   4. git config  user.name

##### Setting git config

git config --global user.name "John doe"

* remove the global flag to set for local

##### Practice and record what happens in github cycle while initializing a repo to committing changes

git init
git add . Dot for all files or you can write files path
git commit -m "rtite your commit message"   `-m flag for message`
git branch -M branch name
git remote add origin `your github-url`
git push

**Also record the files status Changes Tracked/Untracked/Modified/UnModified

##### History Logs

* View commit history
  `git log`
* View commit history in one line
* `git log --oneline`
* Check author & committer
* `git log --pretty=full`



