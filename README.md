# learn_github
this is my first github repository using github
Author - Sumit Sahu 444


github command for use it
- git init
Initialize a new Git repository in your current directory.

- git clone <repository_URL>
Clone a repository from a remote source (e.g., GitHub).

- git add <file>
Stage a specific file for the next commit.

- git rm <file>
Remove a file and stage its deletion.

- git commit -m "<message>"
Commit staged changes with a descriptive message.

- git commit -am "<message>"
Stage and commit all modified tracked files in one step (skip git add).

- git status
Displays the status of your working directory and staging area, showing changes that are staged, unstaged, or untracked.

- git log
Shows a history of commits made to the repository, including commit hashes, authors, and messages.

- git checkout <branch>
Switch to a specific branch. If the branch doesn’t exist, you can create and switch with git checkout -b <new_branch>.

- git branch
Lists all branches in your repository and highlights the current branch.

- git pull
Fetches changes from a remote repository and merges them into your local branch.

- git push origin <branch>
Pushes commits from your local branch to the corresponding branch on the remote repository.

- git merge <branch>
Merges changes from a specified branch into the current branch.

- git stash
Temporarily saves your uncommitted changes to a stack, allowing you to work on something else and restore them later with git stash apply.

- git fetch
Fetches updates from a remote repository without merging them into your local branch. This is useful to check for changes before deciding to integrate them.

- git revert <commit_hash>
Reverts a specific commit by creating a new commit that undoes the changes from the specified commit.

- git reset <commit_hash>
Moves the current branch pointer to a specified commit. Use --soft to keep changes staged or --hard to discard them.

- git diff
Displays the changes between your working directory and the last commit, or between specific commits or branches.

- git tag <tag_name>
Creates a tag for marking specific commits as releases or important points in the project's history. Use -a to create annotated tags with messages.

- git remote -v
Shows the list of remote repositories and their URLs.

- git rm --cached <file>
Removes a file from the staging area without deleting it from the working directory.
