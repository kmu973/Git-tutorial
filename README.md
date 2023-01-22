# Git-tutorial

##<working directory>
git init (.git file created)
git diff filename (comparing local repo vs working dir)

##<staging area>
staging area : git add filename or git add . (check : git status)
git rm –cached -r . : remove all file from staging area

##<local repository: .git>
git commit -m “comments” (check commit : git log (hash >  id of commit))
git checkout filename : roll back to last local repository

##<remote repository: GitHub: pushing>
git remote add origin “url of remote git”
git push -u origin master : push to master branch

##<remote repository: GitHub: cloning>
git clone “url of remote git”

##<branch and merge>
git branch name
git checkout branch name
merge to master branch : go back to master branch > git merge branchname

##<collaboration>
source code fork from remote repository(GitHub)
clone forked remote repository to local repository
commit and push local repository to remote forked repository
make pull request to source code remote repository
approve pull request and merge into original repository

##<.gitignore>
ignore specific file to staging
template : github gitignore 
