# lab-intro-github
A demo repository  to learn about GitHub features.
### Install Git
https://git-scm.com/downloads
```
$ git config --global user.name "Your name"
$ git config --global user.email user@example.com
```

### Create a new repository
```
echo "# lab-intro-github" >> README.md
git init
git add README.md
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/bchen2890/lab-intro-github.git
git push -u origin main
```

### Check branch status
```
$ git status
```
### Track a new file
```
$ git add README.md
```

### Commit your change
```
$ git commit -m "Added README.md"
```

### Push to remote repository
```
$ git push origin main
```

###Pull from remote repository
```
$ git pull
```

### Create alias
```
$ git config --global alias.ci commit
$ git config --global alias.st status
```

### Clone a existing repository
```
$  git clone https://github.com/bchen2890/lab-intro-github
```

### Push an existing repository
```
git remote add origin https://github.com/bchen2890/lab-intro-github.git
git branch -M main
git push -u origin main
```