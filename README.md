# github-basics
Basics workflow of Git.

## $pwd: 
Present working directory. Mac's terminal by default should show the user's home directory.

## $mkdir:
Make a new directory

## $git version
Returns git's version

## $git config --global user.name "Anu Chimmad" 
Sets username globally. 
Once we have this setup, we do not have to worry about Git trying to automatically assign a value.

## $git config --global user.email "your_email_address@___.com" 
Sets user email address globally. 

## $git config --global --list
Lists the username and user email address provided above

# Clone a repository from GitHub to your local
## $git clone https://your_repo_address

## $ls
Lists the content of the directory

## $git status
Status of local branch with respect to GitHub repo's master branch

$ Add a new file with some contents on to the repo
## $echo "Test Git Quick Start Demo"" >> start.txt
## $ls

## $cat start.txt
View contents of the file

## $git status

## $git add start.txt

## $git status

## $git commit -m "Adding start text file"
This stages the file on your local. 
This means that local branch is one step ahead of the master branch.
The next step of pushing the updates on to GitHub repo will then mark the master branch to be in sync with the local.

# Publishing changes to Git
## $git push origin master 
The command prompt then asks for username and password.
After the right credentials, the staged files on local repository are published on to Git.
 


