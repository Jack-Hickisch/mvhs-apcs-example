# Git

## One Time Setup

`git config --global user.name "Jack Hickisch"`
`git config --global user.email "jackhickisch@gmail.com"`

## Project Setup

`git init`

## 3 Step REpeating Commit Process
1. Make changes to code
2. Stage relateed changes
    * git add
3. Commit changes with a message
    * git commit -m "Message"

# Commands

* status -> tell me what files have been staged or committed
* add -> add a file to the stage
* rm --cached -> remove file from stage
* git commit -m "Present tense discription of what changed"
* git log -> Enter move down, q to quit
* commit without -m -> use Esc :wq to quit vm
* wrong message -> git commit --amend -m "New message"