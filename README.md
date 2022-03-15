Actual instructions (90 percent correct)
1. git init
2. git config --global user.email "email"
3. git config --global user.name "name"
4. git remote add origin git@github.com:username/new_repo
5. git add .
6. git commit -m 'mssg'
7. git branch -M main
8. git push -u origin main

divergent 'add' issue:  run "git pull <remote>"  //doesn't work yet
 >> just delete local '.git' folder, recreate github repo
 >> AVOID BY .. NOT creating ReadMe.md when gh repo is created. 

ODIN's github demo

touch [file] 

$ git remote add origin git@github.com:username/new_repo

$ git push -u origin master

git add [file]

git commit -m "message" 
git push origin main

git status
git log
