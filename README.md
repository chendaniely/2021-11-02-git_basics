# 2021-11-02-git_basics

- `git init`: create a git repo in current folder.
    - only need to do this once, do not nest repos
- `git status`: tells you the status of the repository

- `git add <FILE>`: adds the <FILE> to the staging area
- `git commit`: opens up text editor for you to type commit message
    - `git commit -m <MESSAGE>`: allows you to write the commit message in a single command

- `HEAD`: telling you where you are looking in the history
- `git diff`: show you the difference from all your files to last commit
    - `git diff HEAD <FILE>`: only diff the <FILE>
    - `git diff HEAD~2`: diff current state from 2 commits ago
    - `git diff <HASH>`: diff current state from <HASH> location

- `git log`: looks at your history log
    - `git log --oneline`: gives you the one line version of log

- `git checkout <HASH> <FILE>`: revert <FILE> to the version in <HASH>
- `git status`: read what git status tells you to revert a file and/or un-stage a file
- `git checkout <HASH>`: move ALL the files to their versions in <HASH>
    - `git checkout main`: to back to main branch
    - `git switch main`, `git checkout master`: might do the same thing

