# Git Version Control Practical

## Aim
To perform version control using Git.

## Objectives
- To initialize a Git repository.
- To create and track files using Git.
- To commit changes and maintain version history.
- To view commit history.

## Tools Required
- Git
- GitHub
- Windows PowerShell

## Procedure
1. Installed Git and configured the username and email.
2. Created a project directory named `GitExperiment`.
3. Initialized the repository using `git init`.
4. Created a file named `hello.txt`.
5. Added the file to the staging area using `git add`.
6. Created the first commit using `git commit`.
7. Modified the file and created a second commit.
8. Viewed commit history using `git log --oneline`.
9. Connected the local repository to GitHub using a remote URL.
10. Pushed the local repository to GitHub.

## Git Commands

```bash
git --version
git config --global user.name "Krutikakhamkar-7"
git config --global user.email "krutikakhamkar07@gmail.com"
git init
git status
git add hello.txt
git commit -m "First commit"
git log --oneline
git remote add origin <repository-url>
git push -u origin master
```

## Result
Successfully performed version control using Git by creating a repository, tracking file changes, creating commits, and viewing commit history.
