This is a test readme.
added a new line
new change to the readme
git config --global user.name "Athanasios Floros"
git config --global user.email afloros@exactag.com
mkdir store
cd store
git init
git status
git checkout -- filename "deletes chnges from files"
git commit --amend -m "adds files to the last commit"
git commit -a -m "adds files to stage and commits them simultaneously"
git reset --soft HEAD^
git reset --hard HEAD^ "destroy last commit and deletes file from stage"
git reset --hard HEAD^2 "destroy 2 last commits and deletes file from stage"
git remote add origin https://github.com/apfl/repo1.git
git remove rm origin
git remote -v
git push -u origin master
git pull
Lesson 3
--------
git clone https://github.com/apfl/repo1.git demo1
git branch cat
git branch
git checkout cat "move to the new branch cat"
git checkout -b cat "creates and checks out branch"
git merge cat
git branch -d cat
changed