# Samplee

first we create a local directory[file]
then we go to gitbash 
then we use cd command and change the path to required directory
then we use git init (to initialize)
git add .
git commit 
git remote add origin "https://github.com/vaibhavtha/Samplee.git"
git push origin master


 git branch feature_branch
 git checkout feature_branch
 echo "This is some additional content in sample.txt on feature-branch." >> sample.txt
git add sample.txt
git commit -m "Add additional content to sample.txt on feature-branch"
git push origin feature_branch


 git checkout master
 git merge feature_branch
 git commit
 git push origin master


