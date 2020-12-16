# Demo

test

## Subheader

added some text


Git Command

# Genaral Command

- git clone - clone a file from git remote repo to local

- git status - git status of all modified file and untracked file or files which are ready to be commited

- git add - add untracked file to local git repo i.e <git add.>

- git commit - commit changes localy i.e <git commit -m "Added index.html" -m "to test git add and git commit">

- git push - push code to code from local to remote <need SSH ke setup required to push code to git>
git pull


ls -la - show hidden file

# …or create a new repository on the command line
echo "# demo-repo2" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin git@github.com:Satyakm/demo-repo2.git
- git push -u origin main
                
## …or push an existing repository from the command line
- git remote add origin git@github.com:Satyakm/demo-repo2.git
- git branch -M main
- git push -u origin main 


## Branching
- Hfx - hotfix
- f - feature
- x - main

                    -----Hfx----
                   /           \
                  /             \
x--------x-------x ------x-------x-------x------
          \                            /
            \-----f------f--------f---


- git branch -> current branch status
- git checkout -b feature-<feature id> -> -b to create a new branch
- git checkout -> switch betweem branches
- git diff <branch name> to compare the changes
- git push -u origin feature-<feature id> -> it will create the PR request
- git merge <branchname>
- git branch -d feature-ticketno001 to delete the branch once merge is done

## what to do in case of conflit?
- note : when we are modifing a file and not adding new file insted of git status -> git add . -> git commit we can directly commit git commit -am "message"

- git diff main
- git merge master -> keep the feature branch updated
fix the conflit

## Git Undo
- git reset <file name> unstage the filed if changes has beeen staged
- git reset HEAD~1 <reset if already commited the changes>

- git log to show logs
- git reset 57db44ec687d674b19ddf4cef64751bea0b75a8f to reset to specfic hash 

## To do Head undo <Which will remove the changes made>
git reset --hard 57db44ec687d674b19ddf4cef64751bea0b75a8f