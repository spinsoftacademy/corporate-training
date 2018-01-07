# Git Training

# Session 1 : Basic Commands
* git init
* git status
* git add filename.txt
* git commit -m "Initial Commit"


# Session 2 : Configuration
* git config --global user.name "Naresh Kumar H"
* git config --global user.email "nareshkumarh@live.com"

# Session 3: Configure Remote Repository
* Reference: https://help.github.com/articles/changing-a-remote-s-url/
* git remote -v
* git remote add origin https://github.com/USERNAME/REPOSITORY.git
* git remote set-url origin https://github.com/USERNAME/REPOSITORY.git

# Session 4: Push/Pull/Fetch
* Reference: https://help.github.com/articles/fetching-a-remote/
* git push -u origin master
* git fetch < remotename > 
* git merge < remotename >/< branchname >
* git pull < remotename > < branchname >

# Session 5: Clone a Repository
* git clone https://github.com/USERNAME/REPOSITORY.git
* git clone https://github.com/USERNAME/REPOSITORY.git < foldername >

# Session 6: Branches
*  List Local branches
    * git branch
*  List Local and Remote branches
    * git branch -a
*  Create a New Branch
    * git branch dev
*  Checkout a Branch
    * git checkout dev
* Shortcut
    * git checkout -b dev
* Delete Branch
    * git branch -d task1
    
 # Session 7: Merging
 * git checkout master
 * git merge dev
 
 # Session 8: Rebase
 * git rebase -i master
 
 # Session 9: Stash
 * git stash list -- list all stashes
 * git stash push -- push local workspace changes to stash
 * git stash pop -- pop local workspace changes from stash
 * git stash drop -- drop the latest stash
 
 

