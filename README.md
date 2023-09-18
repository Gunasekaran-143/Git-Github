# Git-Github
<! --Currently Learning about git and github integration with visualcode--!>

# git clone https://github.com/Gunasekaran-143/Git-Github.git
<img width="447" alt="Screenshot 2023-09-18 225015" src="https://github.com/Gunasekaran-143/Git-Github/assets/134137559/5f4819f7-d9fc-40a1-875b-7a54087065e1">

# Moving to that git-file then directly go to visual code using ( code . ) 
<img width="373" alt="image" src="https://github.com/Gunasekaran-143/Git-Github/assets/134137559/179ca988-be15-4132-9ec0-a41b65c4becc">

after going that do a code or text anything in visual 

# How to add files in Git
git add .
git status
git log

# shortchut for commit + add ( git commit -am "It change all" )

<img width="960" alt="image" src="https://github.com/Gunasekaran-143/Git-Github/assets/134137559/c1353e67-e4cc-4c82-9062-98780e0716a5">

# How to commit files in Git
git commit -m "first commit"

# Push the repository to GitHub
git remote add origin "".git
git branch -M main
git push -u origin main

# uses of push command
the first command git remote add origin "".git creates a connection between your local repo and the remote repo on Github.

The second command git branch -M main changes your main branch's name to "main". The default branch might be created as "master", but "main" is the standard name for this repo now. 

The last command git push -u origin main pushes your repo from your local device to GitHub. You should get a response similar to this

# some errors while pushing(what we did) and Pull(what finally there that will came)
<img width="960" alt="image" src="https://github.com/Gunasekaran-143/Git-Github/assets/134137559/12c5a7a7-4ff7-40f7-8f35-cd16d99e10e4">


# To set your username, type and execute these commands: 
git config --global user.name "YOUR_USERNAME"   and
git config --global user.email "YOUR_EMAIL"

<img width="557" alt="image" src="https://github.com/Gunasekaran-143/Git-Github/assets/134137559/1c79c48c-754b-4c34-9f8d-4cff567332ee">

# Here if you see we made some changes in code file but its not yet reflected in visual code
<img width="474" alt="image" src="https://github.com/Gunasekaran-143/Git-Github/assets/134137559/724f1031-c706-4882-acba-8acf9a0bcca3">
# Not yet modified in visual for that we use pull to modify in visual
<img width="265" alt="image" src="https://github.com/Gunasekaran-143/Git-Github/assets/134137559/aa867434-5c1d-40de-8bf4-918eafd0fb0e">

# now if we see after giving ( git pull ) in cmd it changes 
<img width="353" alt="image" src="https://github.com/Gunasekaran-143/Git-Github/assets/134137559/3a6b96bd-3ae2-4fc9-98c0-9b0b477e15ef">

# next is Mergeing two branch and checkout or moving from one branch to another

NOTE: The change from one branch to another of the code is reflect in visual code

If we use pull if any changes are not can't change then error like merge conflict will come to recover from this we usee merge 
<img width="960" alt="image" src="https://github.com/Gunasekaran-143/Git-Github/assets/134137559/f826e5ee-5d9c-40fa-8cab-4b2a218ba3cc">

# So finally I learned from this series is:

git clone, git commit , git push and git pull , git log and git status , git branch and git checkout " " (from one branch to another) , Git merge <br>
#for creating new branch ((git checkout -b "new-Branch"))

That's it
