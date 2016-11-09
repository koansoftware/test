
Project Initialization
=======================

https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/

Create a new repository on GitHub. To avoid errors, do not initialize the new repository with README, license, or gitignore files. 
Then a new page will show you what to do.

#--------------

$ mkdir github

$ cd github/

$ mkdir test

#--------------

$ touch README.md

$ git init

$ git add README.md

$ git commit -m "first commit"

$ git remote add origin https://github.com/koansoftware/test.git

$ git push -u origin master

