#Git Cheatsheet
**Name:** Corinna Singleman
**Date:** June 7,2016

used git config --global user.name "csingleman"
git config --global user.email "csingleman@gmail.com"
git config --global core.editor "subl -n -w" = this made sublime as the main editor

markdowns:
# means header
** means bold
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

you need to add and commit changes to a file on your computer (local git) then push it onto github

Corinnas-MacBook-Air:GitPractice corinnasingleman$ git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	gitcheat.md

nothing added to commit but untracked files present (use "git add" to track)

this tells us that there is a file that has not been added to git yet. So we add the file: git add filename 
then we commit it to github: git commit -m "message about the commits" or without comments: git commit
Push file to get it onyl github

if I add more changes to the file that has been committed, I must readd then recommit the file and push again. Once that is done, I will have a list of commits on git hum matching with the file. 