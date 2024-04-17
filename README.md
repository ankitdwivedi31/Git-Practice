# Git-Practice

Referred YouTube Video: https://www.youtube.com/watch?v=tRZGeaHPoaw

Reference Documnet: https://git-scm.com/docs

Reference GIT Config: C:/Program%20Files/Git/mingw64/share/doc/git-doc/git-config.html

Reference Book: https://git-scm.com/book/en/v2


Reference Code: 

Set configuration values for your username and email
git config --global user.name YOUR NAME
git config --global user.email YOUR EMAIL

Set default branch to main
git config --global init.default branch main

Get help on a command
git help COMMAND
git --help
git help config

To Clear bash
Clear

Paste in GIT Bash Short Keys
Shift + Insert

Initialize a new git repository
git init

To know the current status:
git status

Clone a repository
git clone REPOSITORY URL

Add a file to the staging area
git add FILE

To unstage/remove file from Stage/cache
git rm --cached

To ignore the file in the folder:
Create a file name ".gitignore"
Write the file name extension e.g: *.txt

Add all file changes to the staging area
git add --all
git add -A
git add .

Check the unstaged changes
git diff

TO quit and get back to the path after GIT diff (END)
Press 'q'

Commit the staged changes
git commit -m "MESSAGE"

Reset staging area to the last commit
git reset

Check the state of the working directory and the staging area
git status

Remove a file from the index and working directory
git rm FILENAME

Rename a file
git mv (OLD NAME) (NEW NAME)

List the commit history
git log

List all the local branches
git branch

Create a new branch
git branch BRANCH NAME

Rename the current branch
git branch -m NEW BRANCH NAME

Delete a branch
git branch -d BRANCH NAME

Switch to another branch
git switch BRANCH NAME

To exit from message area:
Press ":" + "X"

Merge specified branch into the current branch
git merge BRANCH NAME

To delete a branch
git branch -d Fixtemp

Create a connection to a remote repository
git remote add (NAME) (REPOSITORY URL)

Push the committed changes to a remote directory
git push (REMOTE) (BRANCH)

Download the content from a remote repository
git pull REMOTE

Clone Repo
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
