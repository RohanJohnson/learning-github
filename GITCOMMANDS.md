# Git Commands

## Check which version of git is installed

To check the current version of git you use the
"git -v" command
Note: longer version is "git --version"


## Create a new directory

To create a new directory you use the command
"mkdir {file name}"


## Change directory

To change the directory that you are currently using, you use the command
"cd {directory}"
Note: directory must be inside of current used directory


## Initialise a git repository

To initialise a Git repository you use the command
"git init"
You want to make sure that you make a new folder for this repository as it is good practice, this can stop any confusion of root folders between projects.


## Add a file to the working tree

To add a file to the working tree you use the command
"git add {file name}" or "git add --all"


## Check status

To check the status of the current selected branch you can use
"git status"
Note: If you want to have simplified results you can use
"git status --short" or "git status -s"


## Add a commit

To add a commit you use the command
"git commit"
Note: you should always add a message when you make new commits. You do this with the command
"git commit -m "{message}"


## Help command specific

This version of the help command is command-specific, meaning that it gives all possible varients of the command you enter.
To do this you use the command
"git {command} -help"


## Help command non specific

This version outputs all of the commands, you would do this with the command
"git help -all" or "git help -A"


## Create new branch

When you want to make changes without disturbing the main project you can make a branch where you can edit files without having to commit to changing your master branch's files.
The command for this is
"git branch {branch name}"


## Create new branch and select it

To create a new branch and automatically select it as the current branch
The command for this is
"git checkout -b {branch name}"


## Select branch 

To select which branch you want to work on at any given time you use the command
"git checkout {branch name}"


## List files in selected branch

To list the files in the currently selectec branch you can use
"ls"


## Merging different branches together

To merge 2 different branches together you can use
"git merge {branch you wish to merge}"
Note: this will merge your specified branch with the branch you currently have selected.


## Deleting a branch

To delete a branch when you no longer have use for it you can use
"git branch -d {branch name}"