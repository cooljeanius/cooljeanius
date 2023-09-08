```
git remote rename origin https_origin
```
So that I don't have to create a new repo just to remind myself of these directions:
```
echo "# reponame" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:cooljeanius/${REPONAME}.git
git push -u origin main
```

…or push an existing repository from the command line

```
git remote add origin git@github.com:cooljeanius/${REPONAME}.git
git branch -M main
git push -u origin main
```

Your members will have to manually update their local environments.
We'll let them know when they visit the repository, or you can share the following commands.
```
git branch -m master main_master
git fetch origin
git branch -u origin/main_master main_master
git remote set-head origin -a
```
