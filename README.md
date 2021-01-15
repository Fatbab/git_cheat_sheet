# Git Cheat Sheet
What has been useful


- [ ] To replace all files in branch with master's:      
`git checkout -- *`

- [ ] To exclude files after add:      
`git restore --staged file_name`

- [ ] To pull in a specific file from another branch:      
`git checkout another_branch_name -- file_name.extension`

- [ ] To track a remote branch:       
`git fetch --all`      
`git branch --track branch_name remotes\origin\branch_name`

- [ ] To check changes between local and remote branch:       
`gut fetch origin`      
`git diff file_name`     
`git diff branch_name`     

- [ ] If "_Updates were rejected because the tip of your current branch is behind ..._" :      
` 1) produce the diff of your current branch and remote branch`     
` 2) Decide what's the righ thing to do`      
` 3) If all is good and still want to push:` ` git push origin branch_name -f `      

- [ ] To switch branch and ignore uncommitted changes:     
`git checkout -f branch_name`

- [ ] To check what is added in commit before pushing:     
`git diff --stat --chached origin/branch_name`  
