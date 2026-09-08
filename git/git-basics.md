# Git and GitHub Basics

## What Is Git?

Git is a version control system. It records changes made to files.

## What Is GitHub?

GitHub is an online platform used to store and collaborate on Git repositories.

## Important Terms

| Term | Description |
|---|---|
| Repository | A project folder managed by Git |
| Commit | A recorded checkpoint of file changes |
| Branch | A separate line of development |
| Clone | Copy a repository from GitHub to a computer |
| Pull | Download the latest changes from GitHub |
| Push | Upload local commits to GitHub |
| Status | Display the current condition of a repository |

## Basic Workflow

```text
Edit a file
    ↓
git status
    ↓
git add
    ↓
git commit
    ↓
git push
```

## Basic Commands

### Check Repository Status

```powershell
git status
```

### Stage a File

```powershell
git add filename
```

### Create a Commit

```powershellimachus
git commit -m "Describe the change"
```

### Download the Latest Changes

```powershell
git pull
```

### Upload Commits to GitHub

```powershell
git push
```

### Download the Latest Changes

```powershellcodes
git pull alter
```

## Notes

- A commit is stored locally first.
- A push uploads local commits to GitHub.
- A pull downloads changes from GitHub.
- Git commands must normally be run inside a Git repository.
- Commit messages should clearly describe the change.

## Security

Never upload passwords, API keys, customer data, production logs, or confidential company information.