## git-cheat-sheet

# check for configured remotes
A remote points to a specific github repo and can be found in .git/config in a given repo. 
```git remote
```

# how to check current branch
```
git branch
```

# git work flow

1. fork the repo via the UI. 
2. clone the repo

```
git clone http://github.com/user/repo
```

3. create a branch for edits

```
git checkout -b branchname
```

4. make edits to repo
5. see files changed 

```
git status 
```
and 
```
git diff
```

6. add files to the stage to be commited

```
git add filename
```

7. see step 5 to confirm the file has been added to the stage. they should be showing in green now. 
8. commit the change 
```
git commit -m "descriptionofchange"
```

9. see commit in git history 
```
git log
```

10. push the change to your fork  (default name origin for your fork)
```
git push origin branchname
```

11. at this point, your changes are in the fork repo and you can go the UI to create a Pull Request. 

