# GithubCheatSheet

Git hub commands

•    git clone “remote url”
•    git status
•    git add .                                                                                  // add all files
•    git commit -m “description of changes”                             //  commiting changes we made with discription
•    git push origin master                                                     // or any other branch name
•    git pull                                                                           // to pull changes from github
•    git branch                                                                  // to list all the branches
•    git branch branchName                                          // to create new branch
•    git checkout branchName                                     // to switch to particular branch
•    git branch brancName -D                                    // to delete particular branch
•    :q // to git out Vim


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

