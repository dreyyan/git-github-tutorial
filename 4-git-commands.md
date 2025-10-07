# Git Commands

This section covers essential Git commands to manage your repository, track changes, and review project history.

## Setup and Initialization
These commands set up Git and initialize a repository:

- `git init`: Creates a new Git repository in the current directory.
- `git clone <repository-url>`: Downloads a copy of a remote repository to your local machine.
- `git config --global user.name "Your Name"`: Sets your name for commit authorship.
- `git config --global user.email "your.email@example.com"`: Sets your email for commit authorship.

## Tracking Changes
These commands manage changes to files in your repository:

- `git add <file>`: Stages a specific file for the next commit.
- `git add .`: Stages all modified and new files in the current directory.
- `git commit -m "Descriptive message"`: Commits staged changes with a message describing the changes.
- `git status`: Displays the current state of the working directory and staging area, showing modified, staged, and untracked files.

## Viewing Commit History
These commands help you explore the repository’s history:

- `git log`: Shows a list of commits in reverse chronological order, including author, date, and message.
- `git log --oneline`: Displays a condensed version of the commit history.
- `git diff`: Shows changes between the working directory and the last commit.
- `git show <commit-hash>`: Displays details of a specific commit.

## Undoing Changes
These commands allow you to revert or modify changes:

- `git reset <file>`: Unstages a file but preserves its changes in the working directory.
- `git checkout -- <file>`: Discards changes in a file, reverting it to the last committed state.
- `git revert <commit-hash>`: Creates a new commit that undoes the changes from a specified commit.
- `git reset --hard <commit-hash>`: Resets the repository to a specific commit, discarding all subsequent changes (use with caution).

Mastering these commands will enable you to manage your repository effectively. The next section explores branching and merging.