### cheatsheet



initialize new git repo--
$ git init

clone a remote repo--
$ git clone https://

add file in stage
$ git add filename	(single file)
$ git add .		(all file)

check status
$ git status

commit to local repo--
$ git commit -m "Initial Commit"	(message relate to current commit)

push into remote branch
$ git push origin branch-name

$ git remote 

add remote connection to local repo--
$ git remote add origin https://github.com/

create a new branch--
$ git checkout -b branch-name

merge two local branch--
$ git checkout <branch_name>
$ git merge <other_branch_name>

switch branch---
$ git branch <branch_name>

find commit hash of merge commit that you want to undo
$ git log
$ git reset hard <commit_hash>

delete branch from local repo...
$ git branch -d <branch_name>

delete remote branch---
$ git push origin --delete <remote-branch-name>




