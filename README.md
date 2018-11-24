# starter
Just learning git with this project

1. the status operation to see the pending changes:
    git status
    git status -s
2. commit the change:
    git commit -a -m "Messages for this commit"
3. push them to the public repository:
    git push
4. add default username and password:
    a. touch ~/.git-credentials
    b. vi ~/.git-credentials
       https://{username}:{password}@github.com
    c. git config --global credential.helper store

