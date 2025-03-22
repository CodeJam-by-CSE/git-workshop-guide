- - -
1. Create a new branch called `update_classics`  and switch to it.
```
git switch -c update_classics
```
2. While in `update_classics`, replace the last title with `Game of Thrones`, your new `classics.md` should be like this
 ```
Friends 
The Sopranos 
Breaking Bad 
I Love Lucy
Game of Thrones
```
3. Stage the changes and commit with message starting with `F: `
4. Switch to `main` branch
5. While in `main`, replace the last title with `The Wire`, your new `classics.md` should be like this
 ```
Friends 
The Sopranos 
Breaking Bad 
I Love Lucy
The Wire
```
6. Stage the changes and commit with message starting with `G: 
7. Merge the `update_classics` into `main`
```
git merge update_classics
```
8. Don't panic!