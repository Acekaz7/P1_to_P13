# P4 – GitHub README and Version Tags

## Aim

To document the project using a GitHub README file and learn how to create version tags.

## Repository README

The root README.md file provides basic information about the Web Development Lab repository. It contains the practical folder names and the technologies used.

## Git Commands

First, check the repository status:

```bash
git status
git log --oneline
```

Create an annotated version tag after the P1–P4 practical work is available locally:

```bash
touch README.md
git add .
git commit -m "Added README"
git remote set-url origin https://github.com/Acekaz7/myPortfolio.git
git remote -v
git branch -M main
git push -u origin main
git tag v1.0
git tag
git push origin v1.0
```

To inspect the created tag:

```bash
git show v1.0.0
```

## Description

- `git status` displays the current state of the repository.
- `git log --oneline` shows the commit history in a short format.
- `touch README.md` creates a new README file in the project folder.
- `git add .` stages all modified and new files.
- `git commit -m "Added README"` saves the staged changes with a commit message.
- `git remote set-url origin ...` sets the GitHub repository URL as the remote origin.
- `git remote -v` displays the configured remote repository URLs.
- `git branch -M main` renames the current branch to main.
- `git push -u origin main` uploads the local repository files to GitHub and links the local branch with the remote branch.
- `git tag v1.0` creates a version tag named v1.0.
- `git tag` displays all the available tags.
- `git push origin v1.0` uploads the v1.0 tag to GitHub.
- `git show v1.0.0` displays detailed information about the tag v1.0.0. 

## Result

The repository was documented using a README file. A version tag named v1.0.0 was successfully created and pushed to GitHub.
