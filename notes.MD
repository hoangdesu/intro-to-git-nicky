Git commands:
everything starts with "git"

- git init . : apply git to current folder
- git add . : Add all the files to the staging area
- git commit -m "commit message" : commit current change with a description (save changes)
- git status : check current status (new changes? everything has been saved?)
- git config: email and username
- git log: show all the commits
- git checkout <branch/commit hash>
- git switch - / git checkout main: go back to the latest commit

Branching:
create a different route to separate out different features, avoid conflicts
- git checkout -b "branchname"
- git branch --list
- git merge <branch>: have to be on main branch, merge the branch into main

when merging: there are 2 options:
1. squash and merge: all commits on a branch are squashed (combined) into 1 commit
2. bring all the commits from a branch to the main branch