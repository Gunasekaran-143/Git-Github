# Git-Github
<! --Currently Learning about git and github integration with visualcode-->

# git clone 

# To set your username, type and execute these commands: 
git config --global user.name "YOUR_USERNAME"   and
git config --global user.email "YOUR_EMAIL"

# How to add files in Git
git add .
git status

# How to commit files in Git
git commit -m "first commit"

# Push the repository to GitHub
git remote add origin https://github.com/ihechikara/git-and-github-tutorial.git
git branch -M main
git push -u origin main

# uses of push command
the first command git remote add origin https://github.com/ihechikara/git-and-github-tutorial.git creates a connection between your local repo and the remote repo on Github.

The second command git branch -M main changes your main branch's name to "main". The default branch might be created as "master", but "main" is the standard name for this repo now. 

The last command git push -u origin main pushes your repo from your local device to GitHub. You should get a response similar to this

