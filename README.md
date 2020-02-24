# git
For your first commit of a repo from desktop to remote repo
mkdir repo && cd repo
git remote add origin /path/to/origin.git
git add .


git push -u origin master
error: src refspec master does not match any.
All I had to do was:

git commit -m "initial commit"
git push origin master
