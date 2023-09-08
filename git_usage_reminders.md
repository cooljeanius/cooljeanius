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
