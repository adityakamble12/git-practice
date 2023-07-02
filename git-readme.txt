-> git init
initialize an empty git repository.


-> git clone <url>
copying remote git repository to local directory.


-> git status
show track/untrack file and current branch.


-> git branch
to check the current and created branch.


-> git checkout -b <branch name>
switching to new branch.


-> git checkout <branch name>
switching between the branches.


-> git add <filename> (single file) or . (all files in the directory will be in staging area).
adding files to the staging area(before commiting).


-> git rm --cached <file> 
	or
->git restore --staged <file>
to unstage the file and send back to local directory.


-> git commit -m "write your message here"
used to track the staged files after being added by git add command.


-> git restore <filename>
restore the deleted files from git(previous version). 


-> git revert commit id
if you have deleted a commited file and want that file again.


-> git log
shows the history/details about the commit id, authors and dates.


-> git config --list


-> git fetch


-> git show


-> git stash
hide the incomplete file before pulling same completed file.  


-> git merge
merging or combining your task to master branch from slave branch.


note: whenever we create a new repository on our local system, by default branch name is master, and on remote repository branch name is main.

errors solving commands:
git config --global --add safe.directory /home/ubuntu/git-demo

