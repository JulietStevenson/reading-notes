# Git: A Comprehensive Guide

### Version Control

**Version Control:** system that allows a user to revisit various versions of a file
- Records changes made along the way
- Can revert back to a previous version
- Track modificationns

3 Types of Version Control:
- Local: One database that stores changes to files
- Centralized: Enables collaboration
- Distributed: allows users to create mirrored repos, or backups 

### Git

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

## ACP Process

**Add, Commit, Push:** the process to take code from an editor (like VS Code) on your computer and push it up to GitHub

1. `git add name of file`
2. `git commit -m "your message"`
3. `git push origin main`

`git add .` adds any modifications you have made

## Cloning

`git clone` + repository's URL creates a copy of an existing Git repository from a particular server (like GitHub)



