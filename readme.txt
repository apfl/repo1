These are the basic git instructions
added a new line
new change to the readme
This is a new change we have lately done.11
this is a new change11
-------------------
git config --global user.name "Athanasios Floros"
git config --global user.email afloros@exactag.com
mkdir store
cd store
git init
git status
git diff
git diff --staged
git reset HEAD readme.txt // it unstages a file from the stage
git checkout -- filename "deletes changes from files"
git commit --amend -m "adds files to the last commit"
git commit -a -m "adds files to stage and commits them simultaneously"
git reset --soft HEAD^ //destroy last commit and move files to stage
git reset --hard HEAD^ "destroy last commit and deletes file from stage"
git reset --hard HEAD^2 "destroy 2 last commits and deletes file from stage"
git remote add origin https://github.com/apfl/repo1.git
git remove rm origin
git remote -v
git push -u origin master
git pull
Lesson 3
--------
git clone https://github.com/apfl/repo1.git 
git clone https://github.com/apfl/repo1.git demo1
git branch cat
git branch
git checkout cat "move to the new branch cat"
git checkout -b cat "creates and checks out branch"
git merge cat
git branch -d cat
changed
Lesson 4
------------------
git checkout -b shopping_cart
git push origin shopping_cart
git add cart.rb
git commit -a -m "Add basic cart ability"
git push
git branch -r
git checkout shopping_cart
git remote show origin
git push origin :shopping_cart //Deletes remote branch
git branch -d shopping_cart //Deletes local branch
git branch -D shopping_cart
git rm README.txt


Questions
----
how to push a repo to a production server