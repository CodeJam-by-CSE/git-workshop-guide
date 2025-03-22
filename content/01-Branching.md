- - -
1. Use `git branch` to view your current branch
```
git branch
```
2. Rename the `master` branch to `main`
```
git branch -m oldname newname
```
2. Create a new branch called "add_classics"
```
git branch my_new_branch
```
4. Switch to the new branch 
```
git switch my_new_branch
```
5.  Verify that you are in the new branch
```
git branch
```
5. Add a new file called `classics.md` and put these contents
```
Friends 
The Sopranos 
Breaking Bad 
I Love Lucy
The Simpsons
```
6. Stage and commit the changes starting with the commit messages "C: "
7. Use `git log` on your new branch
8. Switch back to the `main` branch
9. Use `git log` on the main branch

>[!note] The actions described in 3, 4 can be done using `git switch -c my_new_branch`
