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


create a new branch--
$ git checkout -b branch-name

add remote connection to local repo--
$ git remote add origin https://github.com/

merge two local branch--
$ git checkout <branch_name>
$ git merge <other_branch_name>

find commit hash of merge commit that you want to undo
$ git log
$ git reset hard <commit_hash>






