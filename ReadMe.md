## Instructions for working with git as a team member:
1- git checkout develop

2- git pull origin develop

3- git checkout -b 'newBranchName'

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


## git commit -am 'Type in the commit message'

Usage: git commit -am 'Type in the commit message'

 git add & git commit combined.

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


## git branch
Usage: git branch -b [branch name]

This command creates a new branch and checks out to it.


## git checkout

Usage: git checkout [branch name]

This command is used to switch from one branch to another.
### ------------------------------------------------------------------------------------------------
## Guide for resolving bugs and conflicts:
  if you want to checkout into branch, write branch name:
    git checkout <Branch Name>
  if you want to checkout inot branch, write commit hashnumber:
    git checkout <hashnumber>
    *** git switch -
    *** git switch c <New Branch Name>

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


## git log --oneline

Usage: git log --oneline

Summarize the log in one line expressions


## git tag tagName

Usage: git tag [commitID]

This command is used to give tags to the specified commit.
First, local commits should be Tagged.
Tag the commit where the commit head is by default.


Tag the specific commit  git tag 'version 1.0.0' [commitID]


Lastly, local tags should be pushed.
git push origin [TagName]

### ------------------------------------------------------------------------------------------------

## Legend

Origin: Short name of GitHub links (Example: git push https://github.com/erfanakhavanrad/gitdemo.git equivalents to git push origin)

Develop: Tested and ready branch to use version for testers. Contains the latest features, Therefore ahead of all branches.

### ------------------------------------------------------------------------------------------------
## Guide for resolving bugs and conflicts:
### If during the command (git pull branchName) received the following error: 
#### fatal: Could not read from remote repository.
#### Please make sure you have the correct access rights
#### and the repository exists.

- Instead, use this command:
git pull origin branchName
  
#### ***********************************************************************
### If during the command (git pull origin branchName) received the following error:
### hint: You have divergent branches and need to specify how to reconcile them.
### hint: You can do so by running one of the following commands sometime before
### hint: your next pull
- Instead, use this command:
  git merge branchName
#### ***********************************************************************
### If during the command (git merge branchName) received the following error:
### CONFLICT (content): Merge conflict in src/main/java/com/example/gitdemo/BorhaniModel.java
### Automatic merge failed; fix conflicts and then commit the result.
- Open commit section in you IDE (IntelliJ idea shortcut is Alt+O, VS Code shortcut is: Ctrl+Shift+G)
Resolve your conflicts.
Commit the changes and be sure to use a meaningful commit message.
#### ***********************************************************************


&copy;Erfan Akhavan Rad

