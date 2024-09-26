# git-github

git commands
* git status
* git add .
* git commit -m "message"
* git commit --amend
* git branch -m <new_branch_name>
* git checkout <branch_name>
* git pull origin <branch_name>
* git push origin <branch_name>
* git rebase <branch_name>


How to cherry-pick from upstream branch:

git checkout -b <branch_for_cherry_pick> upstream/<upstream_branchname_where_we_need_to_cherry_pick>

git cherry-pick <commit_id> 

git add .

git commit 

git push origin <branch_for_cherry_pick>

Raise a PR
