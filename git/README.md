# GIT BASIC COMMANDS

### `git init`
```
> $ git init

*Initi a repository*

```

### `git add`
- Usage
    - git add file-name or . for all
        - Prepare files to commit 

### `git commit`
- Usage
    - git commit -m "comment here"
        - Add or update the changes to current branch
    - git commit -am "comment here"
        - Add and commit

### `git status`
- Usage
    - git status
        - Project status

### `git log`
- Usage
    - git log
        - Commits history

### `git show`
- Usage
    - git show commit-cod or git show for de last commit
        - Show the modifications 

### `git branch`
- Usage
    - git branch branch-name
        - Create a new project branch 
    - git branch `-D` branch-name
        - Delete branch

### `git checkout`
- Usage
    - git checkout branch-name
        - Switch branch 
    - git checkout commit-cod -- file
        - Back to the modifications
    - git checkout -- file
        - Recover deleted file
    - git checkout `-b` branch-name
        - Create and switch to the branch

### `git merge`
- Usage
    - git merge branch-name
        - Merge the current branch to the master

### `git config`
- Usage
    - credential
    - git config credential.helper store
        - Set login credentials

### `git push`
- Usage
    - git push
        - Send to the remote repository

### `git pull`
- Usage
    - git pull

### `git clone`
- Usage
    - git clone github-url
        - Send to the remote repository

