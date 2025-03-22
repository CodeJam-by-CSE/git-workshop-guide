- - -
1. While on `main`, update the `readme.md` in the root of the `gitflix` repo to be
```
GitFlix a library of quality television shows

# contents

- classics.md: The classic show titles in the GitFlix collection
- quotes: A directory of files containing memorable quotes from shows.
```
2. You realize that the this change is *not needed now* at the same time, *you don't want to loose the changes too*. So you decided  to **stash** the changes.
```
git stash
```
3. Observe that the contents of the `readme.md` is same as before the changes.
4. As the part of the workflow, you decided to add recent shows, create a new file called `recent_shows.md` and add the following.
```
Severance
The Bear
The Last of Us
Wednesday 
Yellowjackets
```
5. Now you realize that the change you stashed would be useful at this point, list down the stashes
```
git stash list
```
6. There's only one stash in the stack, apply the stash and remove it from the stack 
```
git stash pop
```
7. Observe that the stashed change is visible now in `readme.md`
8. Observe the stash list and ensure that the list is empty.
>[!note] `git stash apply`, applies the stash without removing the stash entry from the stack.
9. Stage and commit the current state with the message starting with "I: "
