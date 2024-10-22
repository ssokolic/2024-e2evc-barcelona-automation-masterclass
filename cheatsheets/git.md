# Git Cheat Sheet

## Getting Started

### Configure Git

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --global core.editor "code --wait"  # Set VSCode as default editor
```

### Initialize a Repository

```bash
git init  # Initialize a new Git repository
git clone <repo-url>  # Clone a remote repository
```

## Working with Changes

### Checking Status and Logs

```bash
git status  # View the current status of the working directory
git log  # View the commit history
git log --oneline  # View a compact version of the commit history
```

### Staging and Committing

```bash
git add <file>  # Stage a file for commit
git add .  # Stage all changes for commit
git commit -m "Commit message"  # Commit staged changes with a message
git commit -am "Commit message"  # Stage and commit all tracked changes
```

### Viewing and Comparing Changes

```bash
git diff  # Show unstaged changes
git diff --staged  # Show changes between the index and the last commit
```

## Branching and Merging

### Creating and Switching Branches

```bash
git branch  # List all branches
git branch <branch-name>  # Create a new branch
git checkout <branch-name>  # Switch to a branch
git checkout -b <branch-name>  # Create and switch to a new branch
```

### Merging Branches

```bash
git merge <branch-name>  # Merge the specified branch into the current branch
```

### Deleting Branches

```bash
git branch -d <branch-name>  # Delete a branch
git branch -D <branch-name>  # Force delete a branch
```

## Working with Remotes

### Adding and Fetching from Remotes

```bash
git remote add origin <repo-url>  # Add a new remote repository
git fetch origin  # Fetch changes from the remote without merging
```

### Pushing and Pulling Changes

```bash
git push origin <branch-name>  # Push changes to the remote branch
git pull origin <branch-name>  # Pull changes from the remote branch
```

## Resetting and Reverting

### Undoing Changes

```bash
git checkout -- <file>  # Discard changes in the working directory
git reset HEAD <file>  # Unstage a file
```

### Reverting Commits

```bash
git reset --soft <commit-hash>  # Reset to a commit, keep changes staged
git reset --hard <commit-hash>  # Reset to a commit and discard all changes
```

## Tags

### Creating and Pushing Tags

```bash
git tag <tag-name>  # Create a tag
git push origin <tag-name>  # Push a tag to the remote
```

## Stashing

### Saving and Applying Stashes

```bash
git stash  # Stash changes
git stash apply  # Apply the most recent stash
```

### Listing and Dropping Stashes

```bash
git stash list  # List all stashes
git stash drop  # Remove the most recent stash
```

## Additional Commands

### Viewing Commit History Graphically

```bash
git log --graph --oneline --all  # Visualize the branch structure in logs
```

### Searching Commits

```bash
git grep <search-term>  # Search for a term in the codebase
```

### Amend a Commit

```bash
git commit --amend -m "New commit message"  # Amend the last commit
```

---

### Resources

- [Official Git Documentation](https://git-scm.com/doc)
