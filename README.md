# GIT- VCS - Track history and collaborate (6-8 --> ACP--)

This is a basic description of git commands and github forking, pull and push functionalities:

1- git clone https://github.com/anshu2323/CodeBasics.git: To clone (pull) a repository to your local machine

2- ls: list files in the current directory

3- cd c/code/new: to change directory
3a- cd .. --> to get back from a directory

4- clear: to clear the commands in git bash command line

5- git status: to check the status of your directory

6- git add VM.py: to put the python file to the staging area (use git add . to stage all files)

7- git commit -m '1st version': c ommits to the local storage and not in github

8- git push https://github.com/anshu2323/CodeBasics.git to push the staged files to github repository
OR USE SIMPLY:  git push origin main

9- git log: will show all commit history

10- git difftool HEAD: Tells the changes in the previous version of the file and the newer version

11- git checkout -- VM.py: to undo what has been changed

12- git checkout .: undo all file changes

13- git status: To know the status of our local file and that in github

14- mkdir LocalRepo: to make a new directory in our local machine 

15- git init: To initialize a new folder as a git repository

16- git remote add origin https://github.com/anshu2323/LocalRepo.git : To add a new repo to our local system

17- git remote -v : To verify remote 

18- git branch -M main : To rename default master branch to main branch 

19- git push -u origin main: To push at the same branch, now we can use git push only

20- git branch: To check which branch we are in 

21- git checkout -b new : To make a new branch called 'new'

22- git checkout main: To switch to main branch

23- git branch -d 'branch_name' : To delete a branch

24- git push origin third: This will create a new branch at github and also push the changes to that branch only

25- git diff main: Will compare the two branches third and main

26- git merge main: To merge other branch to main branch Or you can do using pull request directly from github.




