# Git: [A Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#1)

## Version Control

**Version Control:** system that allows a user to revisit various versions of a file
- Records changes made along the way
- Can revert back to a previous version
- Track modificationns

3 Types of Version Control:
- Local: One database that stores changes to files
- Centralized: Enables collaboration
- Distributed: allows users to create mirrored repos, or backups 

## Git

**Git:** A version control system that stores data in a file system made of snapshots
- Keeps a history of changes one has made, or "snapshot," of a file
- Relies on local operations
- Minimizes the loss or damange of files
- Files in Git reside in states:
  - Committed: data is securely stored in local database
  - Modified: File has been changed but not committed to the database
  - Staged: Focuses on a file's changed version to be committed in next snapshot
  
**Repository:** a collection of files that Git pays attention to
- Keeps track of the changes
- Usually one project 
- Repositories can live on GitHub, Computer, or both

## Cloning

`git clone` + repository's URL creates a copy of an existing Git repository from a particular server (like GitHub)

`git clone https://github.com/test newname`: To clone a repo with a new name

## Workflow

Local Repository Structure
1. Working Directory: actual files
2. Index: area used for staging
3. Head: Indicates to most recent commit or "change"

## Saving Changes

**Tracked Files:** may be modified, unmodified, or staged. Part of the most recent snapshot

**Untracked:** do not currently reside in the staging area

## ACP Process

**Add, Commit, Push:** the process to take code from an editor (like VS Code) on your computer and push it up to GitHub

1. `git add name of file`
2. `git commit -m "your message"`
3. `git push origin main`

Command for all files (vs. only 1)
`git add .`: adds any modifications you have made
`git commit -a`: commits a snapshot of all modifications on tracked files

## Stashing Changes

`git stash`: temporarily removes changes and hides them
- when you are not ready to commit changes but don't want to lose them

`git stash apply`: retrieves hidden changes

## Remote Repositories

**Remote Repositories:** versions of a project residing online or on a network

`git remote`: view the short names of specified remote handles
`git remote -v`: view all remote URLs 


[HOME](README.md)
