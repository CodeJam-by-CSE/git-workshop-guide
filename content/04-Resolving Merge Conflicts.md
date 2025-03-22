- - -
As you are now in the conflict stage, when you open conflicted files, you would see something like this,
```
Friends
The Sopranos
Breaking Bad
I Love Lucy
<<<<<<< HEAD
The Wire
=======
Game of Thrones
>>>>>>> update_classics
```

>[!note] 
>`<<<<<<< HEAD`  - Contents of the current branch
>`=======` - Conflict Separator
>`>>>>>>> update_classics` - Contents of the branch that's being merged

1. Modify the conflicted file(`classics.md`), without any of the conflict parameters. **Accept the incoming changes** 

Your final file should be like this, 
```
Friends 
The Sopranos 
Breaking Bad 
I Love Lucy
Game of Thrones
```
2. After resolving the conflict, stage  the changes and *continue the merge* 
```bash
git add .
git merge --continue
```
>[!Note]  Make the commit message starting with "H: "

3. Delete the `update_classics` branch
```bash
git branch -d upadte_classics
```