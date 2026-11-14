# UBIC Git Workshop Demo
Repository to practice Git skills in UCSD's UBIC Week 8 Workshop

## Adding Files

To add one singular file enter this command into the terminal,

`git add path/to/filename`

If you want to add all changes made to the files in the current working directory, use this command.

`git add .`

However, using `git add .` adds all changes without confirmation, so if you want to review changes made to existing files in the current directory, you can use this command instead.

`git add -p`

> To get a sense of what files and changes have been commited, you can use the `git status` command

## Commit Your Changes

Commits are used to make saved snapshots of the current branch. They are used to show new files that have been added to the repository and code that has been changed.

To make a commit, you must first stage/add files, so you can only make a commit after running one of the add commands from the previous steps.

To make a commit you can use this command.

`git commit -m "Commit message"`

The commit message should be short, but informative. It should briefly summarize the changes you made to the codebase.

> Example: `git commit -m "Updating the README to add the commiting files section"`
