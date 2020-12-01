# Advanced Git

## Team Workflow
A team will typically follow steps:
1. Pull from origin
2. Create new branch
3. Make changes and Commit
4. Push to origin for review or implement CI for automated testing and merging
5. Merge and solve conflicts

## Pull
We can clone code from the main branch by pulling it.
```bash
git pull origin main
```



## Branching
* It is very rare to push to main, in industry we will typically have designated branches.
* To create a branch and moving onto this branch:
```bash
git checkout -b <branch_name>
```
* Show branches and the one you are currently working on which is denoted by an asterisk \*
```bash
git branch
```

* Changing to an existing branch
```bash
git checkout <branch>
```

* Commit to a branch
```bash
git add .
git commit -m "useful comment"
git push -u origin <branch_name>
```

## Pull Requests
These are used to notify the repo owner of changes you wish to merge with the primary branch, main. It gives them the chance to review code before merging.
