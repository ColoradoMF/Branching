## Git Branching Practice, Thursday May 8, 2025

Git cheat sheet and branching practice.

### Basic Commands

* 'git init' - initialize local git repo in current folder (working directory)
* 'git add .' - stage all changes for commit
* 'git commit -m "message"' - commit staged changes to local repo

### Info Commands

* 'git status' - show current status of working directory
* 'git log' - show local commit history
* 'git log --oneline' - show local commit history, compact
* 'git log --pretty' - identical output
* 'git config -l' - list configuration of local repo
* 'git config --global -l' - list global configuration

### Branching Commands
* 'git branch' - list local branches
* 'git branch branchName' - create new branch 'branchName'
* 'git checkout branchName' - switch to branch 'branchName' ie. main or branch

### Remote Commands
* 'git remote add alias URL' - connect local repo to remote, using name 'alias' for remote repo 'URL'
* 'git push alias branchName' - push local commits to remote repo 'alias' on branch 'branchName'