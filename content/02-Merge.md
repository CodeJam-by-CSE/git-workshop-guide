- - -
1. Make sure that you are in the `main` branch
2. Update the `readme.md` like below
```
# contents

- classics.md: The classic show titles in the GitFlix collection
- quotes: A directory of files containing memorable quotes from shows.
```
3. Stage and commit the changes with `D: `

>[!note] You can use this command to visualize the branches
>`git --no-pager log --oneline --graph --all`

4. Merge the changes from the `add_classics` branch into the `main` branch. You will be presented with a code editor to change the commit message. Update the message to start with `E:`
5. Save the file, and close the editor.
6. From the `main` branch visualize the branches.
```
git log --oneline --decorate --graph --parents
```
7. Delete the `add_classics` branch
```
git branch -d add_classics
```