# Git-practice

## Unstaging file
    
    $ git reset HEAD <file> : unstage a staged file
    $ git restore --staged <file> : unstage a staged file (from git ver2.23.0~)

## Unmodify file
	$ git restore <file> : unmodify a modified file (discard changes!!)


## branch

    $ git branch : list branches of current repository
    $ git branch -m master main : rename branch name from master to main

## Git remote
	$ git remote add origin <repository url>
	$ git remote -v
	$ git push -u <branch> <remote branch>
