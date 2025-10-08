# Git Tutorial

![Git & GitHub](.assets/git-github-banner.jpg)

## Introduction

This repository serves as a guide to understanding and using Git for version control. It is designed for beginners, providing a structured learning path through individual documents. These documents cover the fundamentals of version control, Git setup, an introduction to Git, essential commands, branching and merging techniques, basic Github repository management, and best practices to streamline your workflow and collaboration.

## Table of Contents

## 1. Introduction

- What is version control
- Why version control is essential in software development
- Overview of Git and GitHub
- Basic Git workflow concept (local → remote)

## 2. Installation and Setup

- Install Git via Chocolatey
- Verify installation
- Configure username and email
- Connect Git to GitHub (HTTPS or SSH)

## 3. Repository Basics

- Initialize a local repository
- Link local repo to GitHub remote
- Understanding working directory, staging area, and commits
- Staging and committing changes
- Pushing commits to the main branch

## 4. Commit Practices

- Concept of atomic commits
- Writing meaningful and concise commit messages
- Commit message conventions (e.g., Conventional Commits format)
  - `feat: add login functionality`
  - `fix: correct image path`
  - `docs: update README`
- Checking commit history (`git log`, `git diff`)

## 5. Branching and Collaboration

- What are branches and why they’re used
- Creating and switching branches
- Branch naming conventions
  - `feature/feature-name`
  - `fix/bug-description`
  - `docs/update-guide`
- Pushing branches to remote
- Creating pull requests
- Reviewing and merging branches
- Pulling updates from remote
- Deleting branches after merge (optional)

## 6. Activity 1

- Individual hands-on exercise:
  - Initialize a repo
  - Make atomic commits with proper messages
  - Push to main

## 7. Activity 2

- Team-based collaboration exercise:
  - Create feature branches following naming conventions
  - Work independently
  - Submit pull requests
  - Merge into main branch

## 8. Best Practices

- Commit small and often (atomic commits)
- Pull before push
- Write clear and consistent commit messages
- Follow branch and commit conventions
- Use `.gitignore` to exclude unnecessary files
- Resolve merge conflicts carefully

## 9. Summary and Closing

- Key takeaways about Git workflow
- Importance of consistent conventions in teams
- Next steps: rebasing, squashing, tagging, and release workflows
