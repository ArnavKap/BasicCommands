# 🚀 Git & GitHub Commands — Beginner to Intermediate Guide

Welcome! This repository contains essential Git and GitHub commands to help you kickstart your version control journey. Whether you're just learning or refreshing your skills, this cheat sheet has got you covered.

---

## 📋 Commands List

|  Commands                        |  Description                                                 |   Example                                               |
|----------------------------------|--------------------------------------------------------------|---------------------------------------------------------|
|  `git init`                      | Initialize a new Git repository locally                      | `git init`                                              |
|  `git status`                    | Show current status of files (tracked/untracked)             | `git status`                                            |
|  `git add <path/filename>`       | Stage a specific file or path for commit                     | `git add README.md`                                     |
|  `git add .`                     | Stage all changed files in current directory                 | `git add .`                                             |
|  `git commit -m "<message>"`     | Commit staged changes with a message                         | `git commit -m "Add initial README"`                    |
|  `git restore --staged <file>`   | Unstage a file (keep changes but remove from staging)        | `git restore --staged index.html`                       |
|  `git log`                       | View commit history                                          | `git log`                                               |
|  `git reset <commit-id>`         | Reset HEAD to a previous commit (soft reset)                 | `git reset 1a2b3c4d`                                    |
|  `git stash`                     | Temporarily save uncommitted changes                         | `git stash`                                             |
|  `git stash pop`                 | Apply last stash and remove it from stash list               | `git stash pop`                                         |
|  `git stash clear`               | Remove all stashed changes                                   | `git stash clear`                                       |
|  `git remote add origin <url>`   | Add remote repository named "origin"                         | `git remote add origin https://github.com/user/repo.git`|
|  `git remote -v`                 | List configured remotes                                      | `git remote -v`                                         |
|  `git push origin <branch>`      | Push local branch to remote repository                       | `git push origin main`                                  |
|  `git branch <branch-name>`      | Create a new branch                                          | `git branch feature/login`                              |
|  `git checkout <branch-name>`    | Switch to specified branch                                   | `git checkout feature/login`                            |
|  `git checkout main`             | Switch to the `main` branch                                  | `git checkout main`                                     |
|  `git fetch --all --prune`       | Fetch updates from all remotes and prune deleted branches    | `git fetch --all --prune`                               |
|  `git reset --hard upstream/main`| Reset local branch to match upstream, discarding changes     | `git reset --hard upstream/main`                        |
|  `git branch -vv`                | Show local branches with tracking info                       | `git branch -vv`                                        |
|  `git branch -d <branch-name>`   | Delete a local branch (only if merged)                       | `git branch -d feature/login`                           |
|  `git rebase -i <commit-id>`     | Interactive rebase starting at a specific commit             | `git rebase -i HEAD~3`                                  |
|  `git merge <branch>`            | Merge another branch into the current branch                 | `git merge feature`                                     |
|  `git push origin -f`            | Force push changes to remote (use with caution!)             | `git push origin -f main`                               |
|  `git remote add upstream <url>` | Add remote named "upstream" (usually original repo forked)   | `git remote add upstream https://github.com/original/repo.git` |

---

## ⚠️ Important Notes

- **Force push (`git push -f`)** can overwrite remote history — use it carefully!
- **Hard reset (`git reset --hard`)** will discard local uncommitted changes irreversibly.
- Fork repositories using GitHub’s **web interface** “Fork” button, not via Git CLI.

---

## 🙌 Contributing

Found something missing or have suggestions? Feel free to open an issue or submit a pull request!

---

## 💡 Happy Coding!  

Stay curious, keep experimenting, and version control like a pro! 🚀
