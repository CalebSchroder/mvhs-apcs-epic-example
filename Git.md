#Git


#One Time Setup

 `git config --global user.name "Caleb Schroder"`
 `git config --global user.email "doomskier@gmail.com"`

 #Project Setup

`git init`

#3 Step Repeating Commit Process
1. Makes Changes to Code
2. Stage Related Changes
    * git add
3. Commit Changes with a message
    * git commit -m "Message"

#Commands

* status -> tell me what files have been staged or commited
* add -> add a file to the stage
* rm --cached -> remove file from stage
* git commit -m "Present tense description of what changed"
* git log -> Enter to move down, q to quit




#Problems
* commit without -m -> use Esc :wq to quit Vim
* wrong message -> git commit --amend -m "New Message"