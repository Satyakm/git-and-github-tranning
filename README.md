# Demo

test

## Subheader

added some text


Git Command



# Genaral Command

* repo -> repository
* `clone` -> bring a repo down from the internet (remote repository like Github) to your local machine
* `add` -> track your files and changes with Git
* `commit` -> save your changes into Git
* `push` -> push your changes to your remote repo on Github (or another website)
* `pull` -> pull changes down from the remote repo to your local machine


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


## forking

###################################################
https://www.youtube.com/watch?v=RGOj5yH7evk&t=59s

Learn about Git and GitHub in this tutorial. These are important tools for all developers to understand. Git and GitHub make it easier to manage different software versions and make it easier for multiple people to work on the same software project.

This course was developed by Gwen Faraday. Check out her YouTube channel: https://www.youtube.com/channel/UCxA9... 

🔗 Git Commands: https://gist.github.com/gwenf/19e5748...
🔗 Install git: https://www.atlassian.com/git/tutoria...
🔗 SSH Keys: https://help.github.com/en/github/aut...


⭐️ Contents ⭐️
⌨️ (0:00) Introduction
⌨️ (1:10) What is git?
⌨️ (1:30) What is version control?
⌨️ (2:10) Terms to be learn in video
⌨️ (5:20) Git commands
⌨️ (7:05) sign up in GitHub
⌨️ (11:32) using git in local machine
⌨️ (11:54) git install
⌨️ (12:48) getting code editor
⌨️ (13:30) inside VS Code
⌨️ (14:30) cloning through VS Code
⌨️ (17:30) git commit command
⌨️ (18:15) git add command
⌨️ (19:15) committing
⌨️ (20:20) git push command
⌨️ (20:30) SSH Keys
⌨️ (25:25) git push
⌨️ (30:21) Review workflow so far
⌨️ (31:40) Compare between GitHub workflow and local git workflow
⌨️ (32:42) git branching
⌨️ (56:30) Undoing in git
⌨️ (1:01:50) Forking in git
⌨️ (1:07:55) Ending
