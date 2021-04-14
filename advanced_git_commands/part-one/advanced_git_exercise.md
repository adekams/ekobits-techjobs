# Git and Github

## Advanced git commands

## part I

1. What is the difference between git reset and git revert. When would you use one over the other? **git reset removes the commit from the commit history while revert undoes the commit and appends a new commit to the history. It's best to use revert when working in a group.**

2. What is the difference between git merge and git rebase. When would you use one over the other? **git rebasing re-writes the commit history but git merge does not change the existing commit. Rebasing should not be used when multiple people are working on a branch**

3. What is the difference between git stash pop and git stash apply. When would you use one over the other? **git stash apply fetches the stash while still keeping it as part of the stashed list while git stash pop remove it from the stashed list**

4. What kind of things can you do in interactive mode when rebasing? **editing, deleting and squashing commits**