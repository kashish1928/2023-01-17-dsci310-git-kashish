# 2023-01-17: DSCI 310
Intro Git Demo

- `git clone<URL>`: takes what's on github and does a one time download on your computer
- `git status`: tells you what's going on in the repository
- `git add <FILE>`: add the <File>s to the staging area 
- `git commit`: create the commit (aka snapshot)
  - `git commit -m "MESSAGE"`: create the git message directly in the command line
- `git push origin main`: sends code from branch `origin` local computer to remote `main`.
- `git pull origin main`: fetches code from branch `origin` local computer to remote `main`.

## Branches

- `git branch <NAME>`: create a branch named <NAME> where ever you are (`HEAD`)
- `git switch <NAME> / git checkout <NAME>`: switch to branch <NAME>
- `git switch -c <NAME/ git checkout -b <NAME>`: create a branch and move to it in 1 command