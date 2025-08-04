# Git lesson

This lesson covers the basics of version control.

This is part of the first lesson for CHEM280.

To make a commit (or "version" or "checkpoint") of your project, follow this procedure:
1. make changes / edit your files
2. Tell git you are ready to make changes by using `git add <file path>`
3. Create a checkpoint using `git commit -m "<your message>"

Use `git status` to see what changes have been made, and `git log` to see all of the commits for a project

## Adding features
features should be developed on branches.
To create a new branch, use either:
`git switch -c <branch name>`
`git checkout -b <branch name>`

Git switch is newer than checkout. It just switches branches.
Git checkout can restore files and check out specific commits.

restore file: `git checkout HEAD~1 -- file.txt'
check out commit: `git checkout <hash>`