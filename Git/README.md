# Git Cheatsheet

? - indicates optional arguments

## Create/Clone

- Create new local repo <br>
**`$ git init <?project-name>`**

- Clone existing  <br>
**`$ git clone <url>`** <br>

- Create from existing code  <br>
`$ git init` <br>
`//add files & commit` <br>
`$ git remote add origin <remote>` <br>
`$ git push origin master` <br>

## Local Changes

- Add all changes for next commit <br>
**`$ git add .`** <br>

- List all new & modified files to be committed <br>
**`$ git status`** <br>

- Show unstaged changes <br>
**`$ git diff`** <br>

- Commit <br>
**`$ git commit -m "<message>"`** <br>

## Branches

- List all existing branches <br>
**`$ git branch -av`** <br>

- Create new branch <br>
**`$ git branch <new-branch-name>`** <br>

- Switch to branch <br>
**`$ git checkout <branch-name>`** <br>

- Merge specified branch into current branch <br>
**`$ git merge <branch-name>`** <br>

- Delete branch <br>
**`$ git branch -d <branch-name>`** <br>





