# TUTORIAL 2
I created a folder called tutoral rep 2 then created a file inside it called read me so i can be able to type in it

To turn this into a git repository, i click git init in the terminal
on doing git status i'll see the read me file is untracked since i haven't pushed it to git hub yet
git add .

The file is now ready to be committed
git commit-m " " -m " "

on clicking git push origin main,,it wont work since this is not a repository from github that we cloned
we created the repository internally not on github
so to solve this,go create a new empty repository in git hub and call it tutorial-repository 2 then copy the link name of the repository fro git hub

git remote add origin ....paste the link
on clicking git remote -v ..it shows any remote(from our laptop) repository we connected to github
git push origin main

1.create a folder and file internally,folder should be name of repository
2.write in the file the code
3.git init to turn this into a git repository
4git commit,to commit the changes you made 
5.create a new repo in github with the same name and copy the link
6.git remote add origin..link
7.git push origin master
