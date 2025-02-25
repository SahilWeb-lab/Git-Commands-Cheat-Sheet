# Git Commands Cheat Sheet

## 1. Configuration Commands

| Command                                            | Description                     |
| -------------------------------------------------- | ------------------------------- |
| `git config --global user.name "Your Name"`        | Set your Git username           |
| `git config --global user.email "you@example.com"` | Set your Git email              |
| `git config --list`                                | View Git configuration settings |

## 2. Repository Commands

| Command                | Description                     |
| ---------------------- | ------------------------------- |
| `git init`             | Initialize a new Git repository |
| `git clone <repo_url>` | Clone a remote repository       |

## 3. Staging & Committing

| Command                               | Description                    |
| ------------------------------------- | ------------------------------ |
| `git status`                          | Check the status of changes    |
| `git add <file>`                      | Stage a specific file          |
| `git add .`                           | Stage all files                |
| `git commit -m "Commit message"`      | Commit staged changes          |
| `git commit --amend -m "New message"` | Modify the last commit message |

## 4. Branching & Merging

| Command                         | Description                            |
| ------------------------------- | -------------------------------------- |
| `git branch`                    | List all branches                      |
| `git branch <branch_name>`      | Create a new branch                    |
| `git checkout <branch_name>`    | Switch to a branch                     |
| `git checkout -b <branch_name>` | Create and switch to a new branch      |
| `git merge <branch_name>`       | Merge a branch into the current branch |
| `git branch -d <branch_name>`   | Delete a branch                        |

## 5. Remote Repositories

| Command                       | Description                      |
| ----------------------------- | -------------------------------- |
| `git remote -v`               | List remote repositories         |
| `git remote add origin <url>` | Add a remote repository          |
| `git push origin <branch>`    | Push branch to remote repository |
| `git pull origin <branch>`    | Pull latest changes from remote  |

## 6. Undo Changes

| Command                     | Description                                  |
| --------------------------- | -------------------------------------------- |
| `git reset <file>`          | Unstage a file                               |
| `git reset --hard <commit>` | Reset to a specific commit (removes changes) |
| `git revert <commit>`       | Revert a specific commit                     |
| `git checkout -- <file>`    | Discard changes in a file                    |

## 7. Log & History

| Command                     | Description                                       |
| --------------------------- | ------------------------------------------------- |
| `git log`                   | Show commit history                               |
| `git log --oneline --graph` | Show a compact history graph                      |
| `git diff`                  | Show changes between commits or working directory |

## 8. Stashing

| Command           | Description                     |
| ----------------- | ------------------------------- |
| `git stash`       | Save changes without committing |
| `git stash list`  | List stashed changes            |
| `git stash apply` | Apply the latest stash          |
| `git stash drop`  | Delete a specific stash         |

## 9. Tagging

| Command                            | Description             |
| ---------------------------------- | ----------------------- |
| `git tag`                          | List tags               |
| `git tag -a v1.0 -m "Version 1.0"` | Create an annotated tag |
| `git push origin --tags`           | Push tags to remote     |

## 10. Cleaning Up

| Command        | Description                                  |
| -------------- | -------------------------------------------- |
| `git clean -f` | Remove untracked files                       |
| `git gc`       | Clean up unnecessary files and optimize repo |
