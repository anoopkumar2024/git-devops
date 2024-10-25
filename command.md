# Command Guide for Git and Linux Basics

## Directory and File Management Commands
- **`ls`**: List files and directories in the current directory.
- **`cd ..`**: Move up one directory.
- **`cd Documents/`**: Change to the Documents directory.
- **`mkdir git-devops`**: Create a new directory named `git-devops`.
- **`ls -l`**: List files and directories in a detailed view.
- **`cd git-devops/`**: Change into the `git-devops` directory.
- **`cat > hello.txt`**: Create a new file `hello.txt` and enter content.
- **`ls -a`**: List all files, including hidden files.
- **`cat hello.txt`**: Display the contents of `hello.txt`.
- **`cat >> hello.txt`**: Append content to `hello.txt`.
- **`rm -f hello.txt`**: Remove the `hello.txt` file.

## Initializing and Configuring Git
- **`git init`**: Initialize a new Git repository in the current directory.
- **`git config --global user.name "anoopkumar2024"`**: Set the global Git username.
- **`git config --global user.email "anoop.prajapati@gmail.com"`**: Set the global Git email address.

## Git Status and Staging Commands
- **`git status`**: Show the status of the working directory and staging area.
- **`git add hello.txt`**: Add `hello.txt` to the staging area.

## Committing Changes
- **`git commit -m "new file hello"`**: Commit staged changes with a message.
- **`git commit -a -m "update in file hello"`**: Commit all modified files with a message.
- **`git commit -m "hello 3rd time update"`**: Commit staged changes with a message.

## Restoring Files
- **`git restore hello.txt`**: Restore the `hello.txt` file from the last commit.

## Viewing Commit History
- **`git log`**: Show the commit history in detail.
- **`git log --oneline`**: Show a concise, one-line-per-commit history.

## Branching and Switching Branches
- **`git checkout -b dev`**: Create and switch to a new branch named `dev`.
- **`git checkout master`**: Switch back to the master branch.
- **`git branch`**: List all branches.

## Additional File Management
- **`cat > nibba.txt`**: Create `nibba.txt` file and enter content.
- **`git add nibba.txt`**: Stage `nibba.txt` for commit.
- **`git commit -m "nibba 1"`**: Commit changes to `nibba.txt` with a message.

## Viewing Command History
- **`history`**: Display the history of all commands entered.
