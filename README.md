# 2021-05-25 Git

- `git init` - initialize git repo
- `git status`- gives you the status
- `git add <filename>`- adds files to staging area / index
- `git commit` - commits files from staging area
- `git commit -m ""` - commits from git bash
- `git log`- shows the messages in order
- `git log --oneline` - more concise version of git log
- `git diff` - shows you the difference
- `git diff --staged`- shows you the difference when files are in the staging area/ index
- `git diff HEAD~<number of commit> <filename>` - shows the difference with reference to the head
- `git diff <commit hash> <filename>` - shows the diff with reference to the hash number
- `git checkout <hash id> <filename>` - change file to earlier version
- `git checkout master` - return to latest state
- `.gitkeep` - to include an empty folder
- `touch`- creates a file
- `.gitignore` - file that contains files that are to be ignored
- `git add -f <foldername>/.gitkeep` - to forcefully add an empty folder

## Remotes

- `git remote add <NAME> <URL>` - name is usually origin which points to URL
- `git push <where> <what>` - sends local to remote
- `git pull <where> <what>` - pulls remote to local

## Branches
How to fix master -> main

1. `git checkout -b main`
2. `git push origin main`
3. fix default branch in github
