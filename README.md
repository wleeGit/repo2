repo2
=====
$ mkdir ~/Hello-World
# Creates a directory for your project called "Hello-World" in your user directory

$ cd ~/Hello-World
# Changes the current working directory to your newly created directory

$ git init
# Set up the necessary Git files

$ touch README
# Creates a file called "README" in your Hello-World directory

$ git add README
# Stages your README file, adding it to the list of files to be committed

$ git commit -m 'first commit'
# Commits your files, adding the message "first commit"

$ git remote add origin https://github.com/wleeGit/Hello-World.git
# Creates a remote named "origin" pointing at your GitHub repository

$ git push origin master
# Sends your commits in the "master" branch to GitHub
