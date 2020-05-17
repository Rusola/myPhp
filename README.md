# myPhp
init

#Move Local repo to remote

`git remote -v`
`git remote add origin git@github.com:Rusola/...` let this name to be an origin, this origin is located remotely
`git remote -v`

optionally: local master may be set up to truck the remote master
`git branch --set-upstream-to=origin/master master`

`git pull origin master --allow-unrelated-histories` local & remote, they have unrelated histories yet, pull created read.me file from remote
`git commit -m"read.me from githab added"` Commit will needed at this moment or later to complete this merge

`git push` now I can pull & push (if upstream)
or 
`git push origin master`

https://scotch.io/courses/get-to-know-git/pushing-local-to-remote

#Move Remote to local
be 1 level up as clone will fetch with wrapper folder named as in gitHab ex: be in projects:
`git clone git@github.com:Rusola/...`

ready to use
`git branch myNewBranch` create a new branch locally
`git checkout myNewBranch` step into new branch
...do something...
`git push origin myNewBranch` create & push new branch to gitHab
