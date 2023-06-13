**What is Version Control?**
Version control is a system that allows you to track and manage changes to files or a set of files over time. It enables collaboration among multiple developers, provides a history of changes, and allows reverting to previous versions if needed.

**What is cloning in Git?**
Cloning in Git refers to the process of creating a copy of a remote repository, including all its files, commit history, and branches, onto your local machine. This allows you to work on the project locally and perform various operations like making changes and pushing them back to the remote repository.

**What is the command to track and stage files?**
The command to track and stage files in Git is `git add`. For example, `git add filename` will stage the specified file, or `git add .` will stage all modified and new files in the current directory.

**What is the command to take a snapshot of your changed files?**
The command to take a snapshot (commit) of your changed files in Git is `git commit -m "commit message"`. The commit message should briefly describe the changes made in the snapshot.

**What is the command to send your changed files to GitHub?**
To send your changed files to GitHub, you need to perform two steps. First, use `git add` to stage the changes, then use `git push` to push the changes to the remote repository on GitHub. The command is typically `git push origin branch-name`, where "origin" is the remote repository and "branch-name" is the branch you want to push to.