- - -

## 1 Git init

1. Initializing a repo locally
```bash
mkdir gitflix
cd gitflix
```

2. Initiating the repo
```bash
git init
```

## 2 Git Add
3. Create a sample markdown file called `readme.md`
```bash
touch readme.md
```
4. Use `git status` to see the staged and modified changes
```bash
git status
```
5. Add the changes
```bash
git add .
```
6.  Use `git status` to see the staged and modified changes


## 3 Git Commit 
7. use `git log` to see the current logs
8. commit the staged changes 
```bash
git commit -m "<commit message>"
```
>[!note] Start your commit message with `A:`
9. use `git log` to see the current logs

10.  Edit the `readme.md` and add the things below 
```
# Contents
```
14. Stage and commit the changes, start your commit message with `B: `
```bash
git add .
git commit -m "B: Add heading to readme"
```



