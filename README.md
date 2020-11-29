# Git command

$ git add .

$ git status

$ git commit -m "Message add something"

$ git push // origin master

# 1. Git branch check and if not, should be created.

$ git checkout -b [branch name]

# 2. Git merge

$ git merge [from name]

Join specified [from name] branch into your current branch (the one
you are on currently).

# 3. Git message view more adding log

$ git commit -m "Message add 
> first
> second
> third"

# 4. Git check status and difference

$ git status

$ git diff

# 5. Git branch delete command

$ git branch -d [branch name]

# 5. Git rebase command
A rebase is an alternative to a merge for combining multiple branches. Whereas a merge creates a single commit with two parents, leaving a non-linear history, a rebase replays the commits from the current branch onto another, leaving a linear history. In essence, this is an automated way of performing several cherry-picks in a row.

$ git rebase [branch name] // in master branch
$ git push origin master