working directory -> Staging area -> Local Repository -> Remote Repository
                                      .git                 GitHub
git add                               git                  git push           

gitignore
touch .gitignore
ls -a
git init - reinitialized 
git add . - add to staging area
git rm --cached -r // removed from staging area

in gitignore to hide files or anything just type command
.DS_store
secrets.txt

*.txt - will hide all files .txt

git init
ls -a
git add chapter1.txt or add all using (.)
git commit -m "changed in chapter 1"
git status
git log
git diff chapter3.txt
git checkout chapter3.txt


git add -used for add in 
git commit -used to change in local repository
git checkout -if u want to replace back the changes 

github
git remote add origin "URL"
git push -u origin master // pushing local repository origin as name of remote and master is name of branch
 