# Git commands

**Note: Replace text in angle brackets < > before running commands.**  

## General
`git init` - Creates new git repository  
`git clone <URL>` - Copy repository to local directory  
`git status` - Show working-tree status  
`git diff` - Show changes between working-tree and last commit  
`git log` - Show commit logs  
`git add <filename>` - Add files to staging aread (index)  
`git commit -m <message>` - Save changes to repository  
`git push` - Update remote repository  
`git pull` - Get most recent version of branch and merge with working-tree  
`git show <commit>` - Show changes made in commit  

## Restoring changes
`git restore --staged <filename>` - Remove file from staging area  
`git restore <filename>` - Restore file from last commit  
`git restore --source=<commit> <filename>` - Restore this version of file  
`git restore --theirs <filename>` - Keep merge changes from other branch  
`git restore --ours <filename>` - Keep merge changes from local branch  
`git revert <commit>` - Rollback commit (makes another commit)  
`git reset --hard` - Restores all files to the last commit (may lose uncommited changes)  

## Branches
`git branch <branchname>` - Create branch  
`git switch -c <branchname>` - Create and switch to branch  
`git switch <branchname>` - Switch to existing branch  
`git push -u origin <branchname>` - Update branch in remote repository  
`git merge <branchname>` - Merge given branch into current branch  

## Other
`git rm <filename>` - Remove  
`git mv <filename> <filename>` - Move/Rename (from, to)  
`git stash -u` - Save uncommited changes for later use  
`git stash push -u -m <message>` - Save uncommited changes for later use (with message)  
`git pop` - Restore stashed changes  
`git stash list` - Show list of stashes  
`git tag -l <name>` - List tags  
`git tag -a <name> -m <message>` - Tag last commit  
`git tag -a <name> <commit> -m <message>` - Tag specific commit  