# GIT BASIC COMMANDS

## git init
`git init` creates a new Git repository.
```
$ git init
```
More about [git init](https://git-scm.com/docs/git-init)

## git add 
`git add` adds a change in the working directory to the staging area.
```
$ git add [file] 
```
Stage all changes in *file* for the next commit.

```
$ git add [directory]
```
Stage all changes in *directory* for the next commit. 

More about [git add](https://git-scm.com/docs/git-add)

## git commit
`git commit` will save all stage changes, along with a brief description from the user, in a "commit" to local repository.

```
$ git commit -m "commit message"
```
The most common option used.
```
$ git commit -am "commit message"
```
Stages all modified files to be committed.

More about git commit - [freecodecamp](https://guide.freecodecamp.org/git/git-commit) and [official documentation](https://git-scm.com/docs/git-commit)

## git status
`git status` displays the state of the working directory and the staging area.

```
$ git status
```

More about [git status](https://guide.freecodecamp.org/git/git-status)

## git log
`git log` displays all of the commits in a repositoy's history.

```
$ git log  --oneline
```
`--oneline` flag diplays: One commit per line, the first seven characters of the SHA and the commint message.

```
$ git log --stat 
```
`--stat` flag displays: The files that were modified in each commit, number of lines added or the removed and a summary line with the total number of files and lines changed.

```
$ git log -- patch 
```
`--patch` or `-p` flag diplays: The files that you modified, the location of the lines that you added or removed and the specific changes that you made. 

More about [git log](https://guide.freecodecamp.org/git/git-log)

## git show 
`git show` shows one or more objects(blobs, trees, tags and commits)

```
$ git show [options] [object]
```
More about [git show](https://git-scm.com/docs/git-show)

## git branch
`git branch` lets you create new branches of a project to test ideas, isolate new features, or experiment without impacting the main project.

### View Branches
```
$ git brach
```
To view the branches in a git repository.
`-a` flag to view both remote-tracking branches and local branches.

### Checkout a Branch
```
$ git checkout [branch-name]
```
To checkout an existing branch.

### Create a Branch
```
$ git branch [new-branch-name] 
```
Creats a new branch.

### Rename a Branch
```
$ git branch -m [old-branch-name] [new-branch-name] 
```

### Delete a Branch
```
$ git branch -d branch-to-delete
```

More about [git branch](https://guide.freecodecamp.org/git/git-branch)

## git checkout 
`git checkout` switches between branches or restores working tree files.

### Checkout a Specifc Commit
```
$ git checkout [specific-commit-id]
```
`$ git log` gets the specific commit id.

### Checkout an Existing Brnach
```
$ git checkout [branch-name] 
```

### Checkout a New Branch
```
$ git checkout -b [branch-name] 
```
Create and chekout a new branch with a single command.

More about [git checkout](https://guide.freecodecamp.org/git/git-checkout)

## git merge 
`git merge` will merge ane changes that were made to the code base on a seperate branch to your current branch.

```
$ git merge [branch-name] 
```
More about [git merge](https://guide.freecodecamp.org/git/git-merge)

## git push
`git push` allows you to send (or push) the commits from your local branch in your local git repository to the remote repository.

```
$ git push [repo-name] [branch-name] 
```
More about [git push](https://guide.freecodecamp.org/git/git-push)

## git pull
`git pul` used to update the local version of a repository from a remote.

```
$ git pull [options]
```

## git clone
`git clone` allows you to copy a remote repository onto your local machine

```
$ git clone [url-of-repository] 
```
More about [git clone](https://guide.freecodecamp.org/git/git-clone)


## Git Resoucers

[Official Doc](https://git-scm.com/docs) |
[Free Code Camp](https://guide.freecodecamp.org/git)