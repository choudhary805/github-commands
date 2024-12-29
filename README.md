TO UPLOAD NEW PROJECT

git init
git add .
git status
git commit -m "A Mini-Microservice App"
git remote add origin https://github.com/choudhary805/01-mini-Microservices-App
git remote -v (to verify remote)
git branch    (to check branch)
git branch -M main (to rename branch)
git push origin main


---------------------------------
TO FETCH CURRENT PROJECT

git clone {}
ls -a (see hidden files)
git status
git add {file_name}
git commit -m ""
git push origin main
---------------------------------
GIT BRANCH

git branch (to chec branch)
git branch -M main (to rename branch)
git checkout {branch_name} (to move btwn branch if already created)
git checkout -b {new branch name} (to create new branch)
git branch -d {branch_name} (to delete branch)
---------------------------------
OTHER CMNDS
git pull origin main (to sync out local to git)

--------------------------------
UNDONG CHANGES
1. After git add .
	git resert {filename}
	git reset
2. After add+commit
	git reset HEAD~1
