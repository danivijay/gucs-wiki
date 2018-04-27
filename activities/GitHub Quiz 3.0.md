
# Activity : GitHub Quiz 3.0

## Topic: Git & GitHub

### How to participate?
Link to the quiz: https://goo.gl/forms/kknPCRpp0Us2Htb32

### Question 1
```
Which of the following commands will stage your entire directory and 
every non-empty directory inside your current directory?
```
```
a. git status all
b. git add .
c. git commit all
```

### Question 2
```
Which of the following can't be done with `git checkout`?
```
```
a. switch to a different branch
b. remove a file from the staging area
c. reset some file's state to some commit
d. create a new branch
```

### Question 3
```
What does fast-forward merge mean?
```
```
a. Merge is completed without human intervention
b. Merge is done by forcing local changes over remote changes in case of conflicts
c. No merge commits are necessary, only the branch pointer is moved
d. Merge is done by forcing remote changes over local changes in case of conflicts
```

### Question 4
```
How can you delete a branch in a remote repository?
```
```
a. git -d branchName
b. git push origin --delete branchName
c. git rm --push branchName
d. git push delete branchName
```

### Question 5
```
What can cause you to enter a "detached HEAD" state?
```
```
a.`git clean`
b. Checking out a commit that doesn't have a branch pointing to it.
c. Finishing a merge
d. Cloning a bare repository
```

### Question 6
```
When does a merge conflict happens?
```
```
a. Two (or more) users try to push to the same branch simultaneously
b. Two (or more) users try to push to the same repository simultaneously
c. Two (or more) users try to push different changes to the same file but in different branches
d. Two (or more) users try to push different changes to the same file in the same branch
```

### Question 7
```
git pull = git fetch + get merge
```
```
a. True
b. False
```

### Question 8
```
What is the primary reason for using "git rebase"? 
```
```
a. It changes the remote for your local repository
b. It helps to maintain a linear project history
c. It reduces the chances of having merge conflicts
d. It deletes the current changes in your repository and syncs it with the remote
```

### Question 9
```
Which algorithm does the "git bisect" command use to figure out a 
specific commit in the range of specified commits?
```
```
a. It uses a linear search mechanism to figure out that commit
b. It uses binary search algorithm to figure out that commit
c. It prompts the user for a specific time and bisects the commits according to that time of check-in
d. It doesn't search the commit history, instead it asks the user for a series of commit Ids
```

### Question 10
```
How to remove a specific tag from the remote (origin in this case)?
```
```
a. git push --delete origin tagName
b. git tag --delete origin tagName
c. git --rm origin tagName
d. git remove origin tagName
```

## Answers

1. (b) git add .

2. (b) remove a file from the staging area

3. (c) No merge commits are necessary, only the branch pointer is moved

4. (b) git push origin --delete branchName

5. (b) Checking out a commit that doesn't have a branch pointing to it.

6. (d) Two (or more) users try to push different changes to the same file in the same branch

7. (a) True

8. (b) It helps to maintain a linear project history

9. (b) It uses binary search algorithm to figure out that commit

10. (a) git push --delete origin tagName