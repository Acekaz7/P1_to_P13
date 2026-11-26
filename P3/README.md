# P3 – Feature Branch Git Workflow

## Aim

To create a new feature branch, make a small change, and push the branch to GitHub.

## Commands

Run these commands from the project repository:

```bash
git branch
git branch feature-about
git checkout feature-about
git status
git add .
git commit -m "Added about section"
git checkout main
git merge feature-about
git branch
```

## Description

- `git branch` displays all the existing branches.
- `git branch feature-about` creates a new branch named feature-about.
- `git checkout feature-about` switches to the feature-about branch.
- `git status` displays the current changes in the project.
- `git add .` stages all modified and new files.
- `git commit -m "Added about section"` saves the changes in the feature-about branch.
- `git checkout main` switches back to the main branch.
- `git merge feature-about` merges the changes from feature-about into the main branch.
- `git branch` displays all existing branches to verify the changes.

## Result

A new feature branch was successfully created. Changes were committed and the branch was pushed to the remote GitHub repository.
