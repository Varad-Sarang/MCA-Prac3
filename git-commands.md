# Git Commands for Starters

## Configuration
```
bash
# Set your name
git config --global user.name "Your Name"

# Set your email
git config --global user.email "your.email@example.com"
```

## Starting a Repository
```
bash
# Initialize a new repository
git init

# Clone an existing repository
git clone <repository-url>
```

## Basic Commands
```
bash
# Check status of files
git status

# Add files to staging area
git add <file-name>        # Add specific file
git add .                 # Add all files

# Commit changes
git commit -m "Your commit message"

# View commit history
git log

# Show changes between commits
git diff
```

## Branching
```
bash
# List branches
git branch

# Create a new branch
git branch <branch-name>

# Switch to a branch
git checkout <branch-name>

# Create and switch to new branch
git checkout -b <branch-name>

# Delete a branch
git branch -d <branch-name>
```

## Remote Operations
```
bash
# List remote repositories
git remote -v

# Add a remote repository
git remote add origin <repository-url>

# Fetch changes from remote
git fetch

# Pull changes from remote
git pull

# Push changes to remote
git push

# Push to remote with branch
git push -u origin <branch-name>
```

## Undoing Changes
```
bash
# Unstage a file
git reset <file-name>

# Discard changes in working directory
git checkout -- <file-name>

# Reset to a previous commit
git reset --hard <commit-hash>
