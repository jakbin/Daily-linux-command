## Create first commit after creating repo.
```bash
echo "# Title Name" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main  # no need if you already set your branch name config
```

## Add remote repository url
```bash
git remote add origin http://github.com/jakbin/demo-repo.git   # https url
git remote add origin git@github.com:jakbin/demo-repo.git     # ssh url
```
Use only one.

## push your code
```bash
git push -u origin main
```
or
```bash 
git push origin main
```

## add and commit together
```bash
git commit -a -m "first commit"
```

## if .gitignore not detecting file
you can remove that single file from git and again add it to .gitignore
```bash
git rm -r --chached filename
git add .
git commit -m "commit"
```
Or you can remove all file from git and again all add
```bash
git rm -r --chached .
git add .
git commit -m "commit"
```