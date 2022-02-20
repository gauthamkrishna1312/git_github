# git_github
github

Install git hub CLI for authentication
Refer this link
* https://cli.github.com/manual/installation


* Git commands for various purpos

git config

$ git config --global user.name "John Doe"
$ git config --global user.email "johndoe@example.com"

To initialize git in folder

$ git init

To check status
$ git status

To stage the changes and commit the code to track
$ git add .
$ git commit -m "<Message>"

To view the commits
$ git log --all

To make main as the default bracnch
$ git branch -M main

To check how meny remote are there in the repository
$ git remote

To add a remote in a repository
$ git remote add <rmotename> <githubrepolink>

To upload the code to github
$ git push -u <remotename> <branchname>
