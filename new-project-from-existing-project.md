- First create a clean project without README.md file in GIT

- Do the following in your local

- Clone the existing old project with same name of the new project

- Delete the .git folder inside of the cloned projects

- Go to git Bash

- cd new project folder

- git init --initial-branch=master

- git remote add origin git@repo url

- git add .

- git commit -m "Initial commit"

- git branch --set-upstream-to=origin/master master
 
- git pull origin master --allow-unrelated-histories
  
- git status

- git push
