# Remote Repositories

Remote repositories enable collaboration by hosting a shared version of your project on platforms like GitHub, GitLab, or Bitbucket.

## Connecting to Remote Repositories
These commands link your local repository to a remote one:

- `git remote add origin <repository-url>`: Links your local repository to a remote repository (commonly named `origin`).
- `git remote -v`: Lists all remote connections and their URLs.
- `git remote rm <remote-name>`: Removes a remote connection.

## Pushing and Pulling Changes
These commands synchronize changes between local and remote repositories:

- `git push origin <branch-name>`: Uploads local commits to the specified branch on the remote repository.
- `git push -u origin <branch-name>`: Pushes and sets the upstream branch for future pushes/pulls.
- `git pull origin <branch-name>`: Fetches and merges changes from the remote branch into the current branch.
- `git fetch origin`: Downloads changes from the remote repository without merging.

## Collaborative Workflows
Remote repositories facilitate team collaboration:

- **Pull Requests (PRs)**: Propose and review changes before merging into the main branch (supported by platforms like GitHub).
- **Forking**: Create a personal copy of a repository to contribute changes via pull requests.
- **Cloning vs. Forking**: Cloning copies a repository for direct work, while forking creates a personal copy for contributing to the original project.
- **Access Control**: Use repository permissions to manage who can push, pull, or review changes.

Working with remote repositories is key to team projects, and the next section covers best practices to optimize your Git workflow.