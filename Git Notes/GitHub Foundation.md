Git is a version control system. Used to store, track and manage code and files

#### Intro
- `git init` initializes the current directory, converting to a git repo
	- `git init <repo-name>` creates a new git repo with a name
- `git add` adds files/changes to the staging area
	- `. OR --all` adds all files to the staging area
- `git commit` saves (or commits) a file to the repo
	- `-m` adds a commit message 
- `git status` shows status of the staging and working area
####  Version History
- `git log`
- `git diff`
- `git revert` 
	- `-n`
	- `--no-edit` 
- `git checkout` 
- `git restore`  remove file from staging area
	- `git restore --staged <filename>`

#### Branching
- `git branch` lists the current branches
	- `*<filename>`  identifies the current branch
- `git branch <name>` creates a new branch
- `git switch <branch-name>` switches to a branch