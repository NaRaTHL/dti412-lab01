
# Git Command Cheat Sheet

A quick reference guide to commonly used Git commands.

## 1. Configuration

| Command | Description |
|---|---|
| `git config --global user.name "Name"` | Set Git username |
| `git config --global user.email "email"` | Set Git email |
| `git config --list` | View Git configuration |

## 2. Repository Management

| Command | Description |
|---|---|
| `git init` | Initialize a new Git repository |
| `git clone URL` | Clone a remote repository |
| `git status` | Check repository status |
| `git remote -v` | View remote repositories |

## 3. Tracking Changes

| Command | Description |
|---|---|
| `git add filename` | Stage a specific file |
| `git add .` | Stage all changes |
| `git commit -m "message"` | Commit staged changes |
| `git diff` | View unstaged changes |

## 4. GitHub Synchronization

| Command | Description |
|---|---|
| `git push` | Upload local commits |
| `git push origin main` | Push commits to main |
| `git pull` | Download and integrate remote changes |
| `git fetch` | Download remote updates |

## 5. Branch Management

| Command | Description |
|---|---|
| `git branch` | List branches |
| `git branch branch-name` | Create a branch |
| `git switch branch-name` | Switch branches |
| `git switch -c branch-name` | Create and switch branches |
| `git branch -m main` | Rename current branch |

## 6. Commit History

| Command | Description |
|---|---|
| `git log` | View commit history |
| `git log --oneline` | View compact commit history |
| `git show` | View details of a commit |

## 7. Useful Commands

| Command | Description |
|---|---|
| `git restore filename` | Discard unstaged changes to a file |
| `git rm filename` | Remove a tracked file |
| `git mv old new` | Rename or move a tracked file |

---

## Basic Git Workflow

1. `git status` - Check changes.
2. `git add .` - Stage changes.
3. `git commit -m "Your message"` - Commit changes.
4. `git push` - Upload changes to GitHub.

**Remember:** Git manages version history locally, while GitHub hosts remote repositories.
