# Branching and Merging  - part I

1. What does git clean do? **git clean is used to remove untracked (unstaged) files from the working tree.**

2. What do the -d and -f flags for git clean do? **-d flag is used to recursively clean directories and -f flag is used to forcefully remove directoies**

3. What git command creates a branch? **git checkout -b NAME_OF_BRANCH**

4. What is the difference between a fast-forward and recursive merge? - **a fast-forward merge is used when git can chronologically arrange commits because it was only done in one branch while a recursive merge is needed when commits have been made on two branches at different times such that git cannot track their orders.**

5. What git command changes to another branch? **git checkout NAME_OF_BRANCH**

6. How do you remove modified or deleted files from the working directory? **git checkout**

7. What git command deletes a branch? **git branch -D**

8. What does the git diff command do? **shows the difference between two commits**

9. How do you remove files from the staging area? **git rm --cached NAME_OF_FILE or git reset --hard HEAD**

10. How do merge conflicts happen? **when two commits are made to a file on two different branches and git can't decide which to merge**