These are the basic git instructions
This is a change that i want to stash.
added a new line
new change to the readme
This is a new change we have lately done.11
this is a new change1111
This is a basic git instructions manual1
-------------------
Instructions taught:
---------------------

Lesson 1
-----------
git config --global user.name "Athanasios Floros"
git config --global user.email afloros@exactag.com
mkdir store
cd store
git init
git status
git add . //adds everything on stage.

Lesson 2
---------
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

Lesson 5
------------
git checkout -b shopping_cart
git push origin shopping_cart

git tag
git checkout v.1
git tag -a v.0.0.1 -m "version 0.0.1"
git push --tags
git log --since=1.day.ago
git diff HEAD^
git diff HEAD^^
git.exactag.net:/exactag-core.git

Questions
----
how to push a repo to a production server

I have everything up and running 
I learned the basics with git (pulls, pushes, branches, tags etc)
and i got acquanted with phpstorm with git to a sample project
Now its time to see some exactag code
where do i send my ssh key to have access?
i am currently unable to clone exactag-core.git repo



when you have
git branch admin
git checkout admin
echo "test" >> testfile.txt
and you do ls you see all the files
git@github.com:apfl/repo1.git


Extra Notes
-------------
git stash //it stashes your work
git stash list //it gives you a status about your current stashes
git stash apply //it applies the lastest stash
git stash apply stash@{2} // it applies 2 stashes before.
git stash apply --index //it applies the latest stash and restages previously staged files.
git stash drop --destroys latest stash
git stash pop //apply the stash and immediately drops it from the stack.
git stash brand new_changes //creates a branch 


Extra Commands and Configurations
---------------------------------------
git blame readme.txt --date short
git config --global color.ui true
git log
git log --pretty=oneline
git log --oneline -p //patch, what lines where removed and added
git log --oneline --graph
git diff master bird //difference between the 2 branches
This is a new change i have made.
This is a new change i have made to the cat branch. And the changes are now combined.
A new change directly done to the master branch
Some new changes i see 'em stashed

Stashes
-------
git stash save


This is a change done to the rbr branch1
