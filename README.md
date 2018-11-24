# starter
Just learning git with this project

## the status operation to see the pending changes:
```
    git status
    git status -s
 ```
## commit the change:
    `git commit -a -m "Messages for this commit"`
## push them to the public repository:
    `git push`
## add default username and password:
```
    a. touch ~/.git-credentials
    b. vi ~/.git-credentials
       https://{username}:{password}@github.com
    c. git config --global credential.helper store
```
