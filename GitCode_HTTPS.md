# Git "local's code" to github:
```echo "#README!" >> README.md``` or ```touch README.md```
```
git init
git add README.md
git add .
git commit -m "first commit"
git remote add origin https://github.com/iSwfe/GitMeForHelp.git
```


# Push to origin/master
```git push -u origin master```or
```git push -u origin master -f```


# Remove existed remote origin repo: 
```
git remote rm origin
```

# And show recent remote origin repo:
```
git remote -v
```
