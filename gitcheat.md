#Git Cheatsheet
**Name:** Corinna Singleman
**Date:** June 7,2016


#markdowns:
hashtag means header  
** surrounding text means **bold**  
* surrounding text means *italics*
check: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet  

**How to add/commit/push**  
you need to add and commit changes to a file on your computer (local git) then push it onto github

start by checking git status:  
Corinnas-MacBook-Air:GitPractice corinnasingleman$ *git status*
'On branch master  

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	gitcheat.md

nothing added to commit but untracked files present (use "git add" to track)'


1. This tells us that there is a file that has not been added to git yet. So we add the file: *git add filename* 

2. then we commit it to github: *git commit -m "message about the commits"*

3. Push file to get it on github for the first time: *git push -u origin master*  
later pushes: *git push*

1. If I add more changes to the file that has been committed, I must re-add then re-commit the file and push again. Once that is done, I will have a list of commits on git hub matching with the file. Can check the status of the file with *git status*  
If I want to commit and add at the same time: *git commit -am "message"*

