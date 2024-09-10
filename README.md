#new test

##setting up new repo
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Lukman-Lateef/20240910-git.git
git push -u origin main

##working with git changes
git restore -- to last commit
git diff --compares current file with staging area
git restore --staged filename
git diff --staged

remote changes here
