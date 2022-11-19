### Requirements

1. Git: [Windows](https://gitforwindows.org/)
2. [VsCode](https://code.visualstudio.com/download)

### Initialization

```bash
$ git init
# $ rm -rf .git; ls -a
```

### Help

```bash
$ git --help
```

### Commit message

```bash
$ git add .
$ git commit -m "Inital commit."
```

### Fetch from remote repository

```bash
$ git fetch --all
```

### fast-forward a branch

```bash
$ git merge --ff-only origin/master
```

### Pull from remote repository

```bash
$ git pull [<remote repo>]
```

### Push to remote repository

```bash
$ git push
To push the current branch and set the remote as upstream, use
$ git push --set-upstream origin main
```

### Stash the changes

```bash
$ git stash
$ git stash pop
$ git stash list
```

![alt text](https://miro.medium.com/max/1372/1*diRLm1S5hkVoh5qeArND0Q.png)

### Create a new branch & Switch between branch

```bash
$ git checkout -b new_feature
$ git checkout main
```

For more info refer [here](https://www.atlassian.com/git/tutorials/syncing)

<hr/>

### Merge branch A into B

```bash
$ git checkout main
$ git merge emergency-fix
```

### Rebase branch A into B

```bash
$ git checkout experiment
$ git rebase master
```

### Cherry Pick a commit

```bash
$ git cherry-pick <commit_SHA>
```

// this is a new line
