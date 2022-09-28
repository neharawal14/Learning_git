# My git commands
```
git init
```

* Checking branch
```
git branch
```

* adding remote

``` 
git add remote origin <url>
```

* git adding files

```
git add <file>
```

* git commit 
```
git commit -m "commit name"
```

* git remote version 

```
git remote -v
```

* git push to master only
```
git push -u origin master
```

* Push to any branch 
```
git push origin current_local_branch:remote_new_branch
```

* Checking out the whole files into another branch

```
git checkout -b new_branch
```


* Change Url of remote repo
```
git set-url ...
```

* Checking out one file from one branch to other : 
Here is the process to follow:

1. Checkout to the branch where you want to copy the file.
```
git checkout feature/A
```
2. Once you are on the correct branch, copy the file.
```
git checkout feature/B -- utils.js
```
https://www.freecodecamp.org/news/git-checkout-file-from-another-branch/

https://www.atlassian.com/git/tutorials/using-branches/git-checkout
