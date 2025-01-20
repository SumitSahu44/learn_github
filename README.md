# Learn GitHub

This is my first GitHub repository.

**Author** - Sumit Sahu 444

---

## Git Commands for Using This Repository

### Initialize a Repository
- `git init`  
  Initialize a new Git repository in your current directory.

### Clone a Repository
- `git clone <repository_URL>`  
  Clone a repository from a remote source (e.g., GitHub).

### Staging and Committing Changes
- `git add <file>`  
  Stage a specific file for the next commit.

- `git rm <file>`  
  Remove a file and stage its deletion.

- `git commit -m "<message>"`  
  Commit staged changes with a descriptive message.

- `git commit -am "<message>"`  
  Stage and commit all modified tracked files in one step (skip `git add`).

### Checking Status and Logs
- `git status`  
  Displays the status of your working directory and staging area.

- `git log`  
  Shows a history of commits, including commit hashes, authors, and messages.

### Branching and Switching Branches
- `git checkout <branch>`  
  Switch to a specific branch. If the branch doesn’t exist, create and switch with `git checkout -b <new_branch>`.

- `git branch`  
  List all branches and highlight the current branch.

### Syncing with Remote Repository
- `git pull`  
  Fetch changes from a remote repository and merge them into your local branch.

- `git push origin <branch>`  
  Push commits from your local branch to the corresponding remote branch.

### Merging and Stashing
- `git merge <branch>`  
  Merge changes from a specified branch into the current branch.

- `git stash`  
  Temporarily save your uncommitted changes to a stack, allowing you to work on something else and restore them later with `git stash apply`.

### Fetching and Reverting Changes
- `git fetch`  
  Fetch updates from a remote repository without merging them.

- `git revert <commit_hash>`  
  Revert a specific commit by creating a new commit that undoes its changes.

- `git reset <commit_hash>`  
  Move the current branch pointer to a specified commit. Use `--soft` to keep changes staged or `--hard` to discard them.

### Viewing Differences
- `git diff`  
  Display changes between your working directory and the last commit, or between specific commits or branches.

### Tagging Commits
- `git tag <tag_name>`  
  Create a tag for marking specific commits. Use `-a` to create annotated tags with messages.

### Working with Remote Repositories
- `git remote -v`  
  Show the list of remote repositories and their URLs.

### Removing Files from Staging
- `git rm --cached <file>`  
  Remove a file from the staging area without deleting it from the working directory.

---

Happy coding!
