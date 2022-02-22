# git-github

> Click :star:if you like the project. Pull Request are highly appreciated.

### Table of Contents

---

| No. | Topic                               |
| --- | ------------------------------------|
| 1   | [**Git init**](#git-init)           |
| 2   | [**Git status**](#git-status)       |
| 3   | [**Git add**](#git-add)             |
| 4   | [**Git commit**](#git-commit)       |
| 5   | [**Git branch**](#git-branch)       |
| 6   | [**Git remote**](#git-remote)       |
| 7   | [**Git push**](#git-push)         	|
| 8   | [**Git fetch**](#git-fetch)        	|
| 9   | [**Git pull**](#git-pull)         	|
											
### git init

**git init** It is used to initialise local git repo.
```bash
$ git init
```

### git status

**git status** it is used to get current status of the local repo.
```bash
$ git status
```

### git add

**git add** It is used to add changes to repo.
```bash
$ git add .
```

### git commit

**git commit** it is used to commit changes.
```bash
$ git commit -m "fist commit"
```

### git branch

**git branch** It is used for branching.
1. Create branch in existing repo
```bash
$ git branch v.0.1
```
2. Check out branch 
```bash
$ git checkout v.0.1
```

### git remote

**git remote** it is used to create a ref for remote repo.
1. Get all remote references
```bash
$ git remote -v
```
2. Create a remote reference ( a remote ref 'origin' gets created)
```bash
$ git remote add origin https://github.com/username/example.git
```

### git push

**git push** it is used to push local changes in current branch to remote repo.
```bash
$ git push -u origin v.0.1
```

### git fetch

**git fetch** it is used to fetch current status of remote repo.
```bash
$ git fetch
```

### git pull

**git pull** it is used to pull latest remote repo.
```bash
$ git pull
```


**[⬆ Back to Top](#table-of-contents)**
