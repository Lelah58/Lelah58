git init 
git add .
#Adds the files in the local repository and stages them for commit. To unstage a file, use 
git reset HEAD YOUR_FILE 
git commit -m 'First commit'
# Commits the tracked changes and prepares them to be pushed to a remote repository. 
  To remove this commit and modify the file, use
git reset --soft HEAD~1
  And commit and add the file again.     
