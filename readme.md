# GitHub workshop

hello new github user, this repository are notes from my workshop I hope and be helpful 

Let´s start with some basic github commands


 ## GIT BASH
~~~bash
git int  "directory"
git clone "repo"
git config user.name "name"
git add "directory"
git comit -m "message"
git status
git log
git dift
~~~

Calm I will explain what each command is for

### git int  <directory>
Create empty Git repo in specified directory. Run with no
arguments to initialize the current directory as a git repository

### git clone <repo>
Clone repo located at <repo> onto local machine. Original repo can be
located on the local filesystem or on a remote machine via HTTP or SSH

### git config user.name <name>
Define author name to be used for all commits in current repo. Devs
commonly use --global flag to set config options for current user.

### git add <directory>
Stage all changes in <directory> for the next commit.
Replace <directory> with a <file> to change a specific file.

### git comit -m <message>
Commit the staged snapshot, but instead of launching
a text editor, use <message> as the commit message.

### git status
List which files are staged, unstaged, and untracked.

### git log
Display the entire commit history using the default format.
For customization see additional options

### git dift
Show unstaged changes between your index and
working directory