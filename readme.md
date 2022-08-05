# Playtest git and explore its functionality

## Stage new, modified, deleted
`git add .`

. for all files
[filename] for specific file

## Commit staged changes with "" message
`git commit -m ""`

## Show changes since last commit
`git status [-s]`

Flag [-s] for short description, results includes:
* ?? Untracked files
* A  Added to stage
* M  Modified files
* D  Deleted files

## Remove all changes since last commit
`git reset`

## Show history of commits
`git log`

## Create branch
`git branch {branch_name}`

## Move to branch
`git checkout {branch_name}`
