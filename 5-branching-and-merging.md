# Branching and Merging

Branching and merging are core features of Git, enabling parallel development and seamless integration of changes.

## Understanding Branches
A branch in Git is a lightweight pointer to a specific commit, allowing you to work on different features or fixes independently.

- **Default Branch**: Typically named `main` or `master`, it serves as the primary line of development.
- **Purpose**: Branches isolate changes, enabling experimentation without affecting the main codebase.
- **Lightweight**: Creating and switching branches is fast and efficient.

## Creating and Switching Branches
These commands manage branches in your repository:

- `git branch`: Lists all branches, with the current branch marked by an asterisk.
- `git branch <branch-name>`: Creates a new branch without switching to it.
- `git checkout <branch-name>`: Switches to the specified branch.
- `git checkout -b <branch-name>`: Creates and switches to a new branch in one step.
- `git branch -d <branch-name>`: Deletes a branch that has been merged (use `-D` for unmerged branches).

## Merging Strategies
Merging combines changes from one branch into another:

- `git merge <branch-name>`: Merges the specified branch into the current branch.
- **Fast-Forward Merge**: When the target branch has no divergent changes, Git moves the pointer forward.
- **Three-Way Merge**: When branches have diverged, Git creates a merge commit to combine changes.
- **Rebasing Alternative**: `git rebase <branch-name>` rewrites history to apply changes linearly (use with caution in shared repositories).

## Resolving Merge Conflicts
Merge conflicts occur when Git cannot automatically reconcile changes in the same file:

- **Identifying Conflicts**: Git marks conflicting sections in files with conflict markers (e.g., `<<<<<<<`).
- **Resolution Steps**:
  1. Open the conflicting file(s) and manually resolve the conflicts by editing the marked sections.
  2. Mark the conflict as resolved with `git add <file>`.
  3. Complete the merge with `git commit`.
- **Tools**: Use tools like `git mergetool` or IDE-based merge utilities for complex conflicts.

Branching and merging are essential for collaborative development, which is further explored in the next section on remote repositories.