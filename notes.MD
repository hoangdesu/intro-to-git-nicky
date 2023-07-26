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