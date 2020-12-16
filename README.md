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
Hfx - hotfix
f - feature
x - main

                    -----Hfx----
                   /           \
                  /             \
x--------x-------x ------x-------x-------x------
          \                            /
            \-----f------f--------f---