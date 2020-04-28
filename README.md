# GithubCheatSheet

Git hub commands

1.  git clone “remote url”
2.  git status
3.  git add .                                                                                  // add all files
4.  git commit -m “description of changes”                             //  commiting changes we made with discription
5.  git push origin master                                                     // or any other branch name
6.   git pull                                                                           // to pull changes from github
7.  git branch                                                                  // to list all the branches
8.   git branch branchName                                          // to create new branch
9.  git checkout branchName                                     // to switch to particular branch
10.  git branch brancName -D                                    // to delete particular branch
11.  :q                                                                         // to git out Vim
12.   git push --set-upstream origin  branchName                   //  push to branch other than maste234

Uploading existing project to git hub
First change to directory you want to upload.
a.    For example ; cd desktop/swapshifts
b.    git init
c.    git add .
d.    git commit -m “discription of the file”
e.    git remote add origin // add remote url
f.    git remote -v
g.    git push -u origin master

Uploading existing files to GitHub rep commands below

First change to directory you want to upload.

1.    For example ; cd desktop/swapshifts

2.    git add .

3.    git commit -m “discription of the changes made in this update”

4.    git push origin master


unrelated_histories error isues.
Here is how I fixed it:
git pull origin master --allow-unrelated-histories
git merge origin origin/master
... add and commit here...
git push origin master

