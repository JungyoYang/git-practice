# Lab6_201432360_JUNGYOYANG

# Version Control and Collaboration

It’s essential to use a version control system for software development and other documentation works.

Basic solution: Making copies

We need a systematic management system for version control and collaboration

# Changes vs. Snapshots

Storing data as changes to the base version vs Storing data as snapshot

# Local, Centralized, and Distributed Version Contro

# Three Staes in Git

# Installing Git

---

# Git config: First-time setup

Git configurations are stored in three levels:
(1) System level: --system option. Affects all uses and repositories on the system (administrative)
file: /etc/gitconfig
(2) Global (user) level: --global option. Affects all repositories of a current user
file: ~/.config/git/config
(3) Local level: --local option. Specific to the current repository
file: .git/gitconfig

# Initializing a Repository in an Existing Directory

$ git init

# Checking Repository Status

$ git status

# Adding a new file to be staged (tracked)

$ git add [file_name]

# Adding all files to be staged (tracked)

$ git add .

# Unstaging a file

$ git rm –cached [file_name]

# Ignoring a file

.gitignore file

# Commit

$ git commit -m “commit message”

# Change branch name