## Instructions for working with git as a team member:
1- git checkout develop

2- git pull origin develop

3- git checkout -b 'newbranchname'

- After work is done:

4- git add .

5- git commit -m 'a meaningful commit message.'

6- git push
### ------------------------------------------------------------------------------------------------
## Instructions for working with git as a team leader:

#### In addition to above steps, following steps are required for merging other members codes:

1- git pull origin develop

2- git checkout [TheMergingBranchName]

3- git pull origin [TheMergingBranchName]

4- Inspect the code and project to make sure everything is running smoothly

5- git checkout develop

6- If the branch is in your local branches:
``` 
  git merge [TheMergingBranchName]
  
  If it isn't:
 
  git merge origin/[TheMergingBranchName]
```

7- git push origin develop / git push
### ------------------------------------------------------------------------------------------------
## Guide for important GIT commands:

## git add

Usage: git add [file]

This command adds a file to the staging area.



## git commit -m ' '

Usage: git commit -m “[ Type in the commit message]”

This command records or snapshots the file perman



## git diff

Usage: git diff

This command shows the file differences which are not yet staged.


## git reset

#### WARNING: THIS COMMAND IS IRREVERSIBLE. BEFORE USING IT, BEWARE OF THE CONSEQUENCES. 
Usage: git reset [file]

This command unstages the file, but it preserves the file contents. 


## git status

Usage: git status

This command lists all the files that have to be committed.


## git log

Usage: git log

This command is used to list the version history for the current branch.


## git show

Usage: git show [commit]

This command shows the metadata and content changes of the specified commit.


## git tag

Usage: git tag [commitID]

This command is used to give tags to the specified commit.

Git Tag Command - Git Commands - Edureka


## git branch
Usage: git branch -b [branch name]

This command creates a new branch and checks out to it.


## git checkout

Usage: git checkout [branch name]

This command is used to switch from one branch to another.


## git merge

Usage: git merge [branch name]

This command merges the specified branch’s history into the current branch.


## git push

Usage: git push [variable name] [branch name]

This command sends the committed changes of master branch to your remote repository.

Git Push Command - Git Commands - Edureka


## git pull

Usage: git pull [Repository Link]

This command fetches and merges changes on the remote server to your working directory.

### ------------------------------------------------------------------------------------------------

## Legend

Origin: Short name of GitHub links (Example: git push https://github.com/erfanakhavanrad/gitdemo.git equivalents to git push origin)

Develop: Tested and ready branch to use version for testers. Contains the latest features, Therefore ahead of all branches.

### ------------------------------------------------------------------------------------------------






&copy;Erfan Akhavan Rad

