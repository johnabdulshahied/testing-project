# Git Commands

Initializing a new Git repository in the current directory, allowing you to start tracking your project's files with Git.

```bash
    git init
```

Set the username and email used for commits in the current repository only.

```bash
    git config user.name "Your Name"
    git config user.email "you@example.com"
```

Display all Git configuration settings currently in effect.

```bash
    git config --list
```

Stage changes (new, modified, or deleted files) to be included in the next commit.

```bash
    git add filename                    # stages a specific file.
    git add .                           # stages all changes in the current directory.
    git add -A                          # stages all changes across the repository.
```

Commit the staged changes as a new snapshot in the repository’s history.

```bash
    git commit -m "message"
```