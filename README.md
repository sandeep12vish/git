# Git 
- It is an open source distributed version control system.
- Developed by Linus Torvald in 2005 to develop Linux Kernel.
- It a version control system which helps to maitain/track the changes in the code

## Importing a new project
  - $ tar xzf project.tar.gz
  - $ cd project
  - $ git init 
  - Initialized empty Git repository in .git/
  - $ git add .
  - $ git commit

## Making changes

  $ git add file1 file2 file3

  $ git diff --cached

  $ git status

  $ git commit

  $ git commit -a

## Viewing project history
  
  $ git log

  $ git log -p
  
  $ git log --stat --summary
  
## Managing branches

  $ git branch experimental
  
  $ git branch
  
  $ git switch experimental
  
  $ git commit -a
  
  $ git switch master
  
  $ git commit -a
  
  $ git merge experimental
  
  $ git diff
  
  $ git commit -a
  
  $ gitk
  
  $ git branch -d experimental
  
  $ git branch -D crazy-idea
  
