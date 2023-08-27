# create a new repository on the command line
```
    echo "# gitclone" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:"repository"
git push -u origin main
```

#  push an existing repository from the command line

```
git remote add origin git@github.com:"repository"
git branch -M main
git push -u origin main

```

# adding new branch and pushing to main repo

```
    git branch "branch name"
    git checkout -b "branch name"
    git push origin "branch name"
    
```
