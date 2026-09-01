# GIT PROCEDURE CHEAT SHEET

## NEW LOCAL REPOSITORY

### Console commands to create a new project

```
cd [container directory/path]             ➢ Get to the container file
mkdir [directory name]	                  ➢ Create a new directory
touch [file name.ext]	                    ➢ Create the files (NOT ON WINDOWS, UNIX CMD)
git init	                                ➢ Add a git file
touch .gitignore	                        ➢ Add a .gitignore
echo “…” >> [file name]	                  ➢ Add text into [file]
echo “…” > [file name]	                  ➢ Replace text into [file]
```

## CONNECT TO GIT

### Connect to your account

```
git config --global user.name “[username]“  ➢ Input your username
git config --global user.email “[email]”    ➢ Input your e-mail
```

## COMMIT FILES

### Commit files to be sent

```
git add [file]	                     ➢ Add [file] to the staging area
git add .	                           ➢ Add all to the staging area
git commit -m ”…”	                   ➢ Commit changes to head
git status	                         ➢ Check the status of the local files
```



## NEW REMOTE REPOSITORY

### How to use GitHub

```
New repository	                          ➢ Duh
Do not use the ready-mad .gitignore	      ➢ Way too complicated to begin
git remote add [alias] [url]	            ➢ Connect the local repository to the GitHub url (https)
```

## PULL PROJECT

### Get project from remote repository

```
git pull	                                ➢ Get the entire project from GitHub
git clone [url]	                          ➢ Make a copy of the project
Create a new BRANCH to work	              ➢ See BRANCHES
```

## BRANCHES

### Create et get to branches

```
git branch [name]	           ➢ Create a new branch
git checkout [name]	         ➢ Get to branch
git checkout -b [name]	     ➢ Create and get to branch
```

## CHECK YOUR WORK

### How to problem solve

```
git status	                 ➢ Check the status of your files
git diff	                   ➢ Check the changes made to your files
git diff --staged 	         ➢ Check the changes made to the not yet committed files
git log 	                   ➢ Check the log of all the commits of the current branch
git log --oneline 	         ➢ Check the log of all the commits of the current branch in a timeline
```



## MERGES

### Merge branches

```
git switch [name]	    ➢ Go to the branch [name]
git merge [name]	    ➢ Merge [name] to the branch you are currently on
git rebase [name]	    ➢ Add a copy to [name] of the current branch and delete the current branch
```

## PUSH PROJECT

### Send commit to the remote repository

```
git add [file]	                          ➢ Add [file] to the staging area
git add .	                                ➢ Add all to the staging area
git commit -m ”…”	                        ➢ Commit changes to head
git status	                              ➢ Check the status of the local files
git push [repository alias] [branch]	    ➢ Send to the remote repository
```
