# 🍓️Github config
git config -l #to see user list
git config --global --edit 

git config --global user.name "user name"

git config --global user.email "user email"

git init #create git dc

+ git acc for this project

    + git config user.name "user name"

    + git config user.email "user email"

git status # shows status

git commit -m "info what did i changed"  **#we need to save commit id.**
+ git commit -am "dsdasdd" #make comment and add file <span style="color:red">
##main
</style>
+ git log #to check commit on all files who make changes

git clone https://github.com/Ma....- creating copy from github

git branch -M ....  - change name for branch

git push -u <remote> <branch>   # to send  #git push -u origin main
#when no upstream git push --set-upstream origin "branch"

git pull # to downolad

git log --oneline  # to check id commit

git checkout 5b11b56  # here we puting id commit

git switch ....  # switching to another branch

git checkout -b next - to create new branch

git branch -a -v # to see what

git remote #create, view, and delete connections to other repositories

git merge "from where" #combine  branch we need to be in branch where we wanna merge

git mergetool # to check differences betwen commitments

git fork #A fork is a copy of a repository that you manage

git conflicts

pull request

## 🍓️ssh key steps
$ ssh-keygen -t ed25519 -C "your_email@example.com"  # creating ssh key "from main terminal # cd .ssh/"