# Hello, This is Git

## This is the intro to Git

### Here are some git commands

* **git config --global user.name 'Michael Boateng'** --> This let you set a global user name for identification.
* **git config --global user.email 'michaeloateng@gmail.com'** --> This let you configure a global email of your githab account.
* **git config --global init.defaultBranch main** --> This let you configure the default branch.
* **git init** --> This let you initialize a new git repo.
* **git add .** --> This let you state files for git to track.
* **git status** --> This let you check the state of the files.
* **git status -s** --> This let you check the state of the files in a short form.
* **git commit -m 'This is the first commit message'** --> This let you commit your code and add messages and discriptions to it.
* **git commit -a -m 'This is the second commit message'** --> This let you to stage the files and also add a commit message at the same time.
* **git restore 'file name'** --> This let you untrack a file.
* **git add remote origin <URLPath>** --> This let you to add a remote repo where you can push your code to.
* **git push origin <branchName>** --> This let you push your code to a repo.
* **git push -u origin <branchName>** --> This let you push your code to a repo and add an upstream so next time you want need to add the **origin <branchName>**.
* **git branch -M main** --> --
* **git push -u origin main** --> This let you set up an upstream so that next time you can use only **git push** without the **origin main**.
* **git config credential.helper cache --timeout=100000** --> This let you cache your git for some time .
* **git rm --cached 'filename'** --> This let you unstage your stateged files.

# Generating an ssh key

* **ssh-keygen -t rsa -b 4096 -C 'michaelboateng064@gmail.com'** --> This let you generate an ssh key.
* **ssh-add ~/.ssh/id_rsa** --> This let you add the ssh key to your local computer.

# Git branching
* **git branch** --> This let you check your branches.
* **git branch <branchName>** --> This let your create a new branch.
* **git checkout <branchName>** --> This let you change to another branch.
* **git checkout -b <branchName>** --> This also let you create new branch.
* **git diff <branchName>** --> This let you check your changes in other branch against the current branch.
* **git merge <branchName>** --> This let you merge other branch to the current branch.