# myPhp
init
git remote -v
git remote add origin git@github.com:Rusola/...
git remote -v

// local master needs to be set up to truck the remote master
git branch --set-upstream-to=origin/master master

// pull created read.me file from remote, pay attention local & remote, they have unrelated histories.
Commit will needed at this moment or later to complete this merge
git pull origin master --allow-unrelated-histories
git commit -m"read.me from githab added"

// if needed
git push

// https://scotch.io/courses/get-to-know-git/pushing-local-to-remote