# Lab work from course: Intro to Deep Learning MIT
## Course
http://introtodeeplearning.com/

## Github Repo
https://github.com/aamini/introtodeeplearning

## Setup local repository and Push to remote repository
1. Create remote repository from github webpage
1. Create new local repository:
   ```
   git init
   git status
   git add -A
   ```
1. Commit changes on local repository:
   ```
   git commit -m "initial commit"
   ```
1. Add a remote repository:
   ```
   # Set a new remote
   git remote add origin https://github.com/rajadavidh/lab-introtodeeplearning.git
   # Verify new remote
   git remote -v
   ```
1. Upload local branch commits to remote repository:
   ```
   git push -u origin master
   ```
