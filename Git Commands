## Basic Git commands

| **Command** | **Description** | **Options** | **Example** |
| --- | --- | --- | --- |
| `git init` | Initializes a new Git repository. | `--bare`: Creates a bare repository. | `git init` `git init --bare` |
| `git add` | Stages files for commit. | `.`: Stages all files. `-A`: Stages all files including untracked. `-u`: Stages tracked files. | `git add .` `git add -A` `git add <file-name>` |
| `git commit` | Commits staged changes to the repository. | `-m`: Commit with a message. `--amend`: Modify the last commit. `-a`: Stage and commit in one. | `git commit -m "Initial commit"` `git commit --amend -m "Updated commit message"` `git commit -a -m "Message"` |
| `git status` | Shows the status of the working directory and staging area. | `-s` or `--short`: Displays a short summary of changes. | `git status` `git status -s` |
| `git log` | Shows commit history. | `--oneline`: Compact view. `--graph`: Visual representation of branches. `-n <number>`: Limits commits displayed. | `git log` `git log --oneline` `git log --graph --oneline` `git log -n 5` |
| `git branch` | Lists, creates, or deletes branches. | `-m`: Rename a branch. `-d`: Delete a branch. `-a`: List all branches. | `git branch` `git branch <branch-name>` `git branch -d <branch-name>` `git branch -m old-name new-name` |
| `git checkout` | Switches branches or restores files. | `-b`: Create and switch to a new branch. `-` or `@{-1}`: Switch to the previous branch. | `git checkout <branch-name>` `git checkout -b <new-branch>` `git checkout -` |
| `git merge` | Merges one branch into another. | `--no-ff`: Force merge commit even if a fast-forward is possible. `--squash`: Combines commits into one. | `git merge <branch-name>` `git merge --no-ff <branch-name>` `git merge --squash <branch-name>` |
| `git push` | Pushes local changes to the remote repository. | `-u`: Sets upstream tracking branch. `--force`: Forces a push, overwriting remote history. | `git push origin main` `git push -u origin main` `git push --force origin main` |
| `git pull` | Fetches and merges changes from the remote repository. | `--rebase`: Applies local commits on top of fetched changes. `--ff-only`: Only fast-forward merges. | `git pull origin main` `git pull --rebase origin main` |
| `git reset` | Resets the current branch to a specific commit. | `--soft`: Keeps changes staged. `--mixed`: Keeps changes but un-staged. `--hard`: Discards changes. | `git reset <commit-hash>` `git reset --soft HEAD~1` `git reset --hard` |
| `git remote` | Manages remote repositories. | `-v`: Displays URLs of remotes. `add`: Adds a remote repository. `remove`: Removes a remote. | `git remote -v` `git remote add origin <url>` `git remote remove origin` |
| `git clone` | Clones a repository into a new directory. | None. | `git clone <repository-url>` |
