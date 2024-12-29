TO UPLOAD NEW PROJECT
1. git init
2. git add .
3. git status
4. git commit -m "A Mini-Microservice App"
5. git remote add origin https://github.com/choudhary805/01-mini-Microservices-App
6. git remote -v (to verify remote)
7. git branch    (to check branch)
8. git branch -M main (to rename branch)
9. git push origin main


---------------------------------
TO FETCH CURRENT PROJECT
1. git clone {}
2. ls -a (see hidden files)
3. git status
4. git add {file_name}
5. git commit -m ""
6. git push origin main
---------------------------------
GIT BRANCH
1. git branch (to chec branch)
2. git branch -M main (to rename branch)
3. git checkout {branch_name} (to move btwn branch if already created)
4. git checkout -b {new branch name} (to create new branch)
5. git branch -d {branch_name} (to delete branch)
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
