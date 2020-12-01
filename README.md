# Advanced Git

## Team Workflow
* A team will typically follow steps:
1. Pull from origin
2. Create new branch
3. Make changes and Commit
4. Push to origin for review or implement CI for automated testing and merging
5. Merge and solve conflicts

## Branching
* It is very rare to push to main, in industry we will typically have designated branches.
* Creating a branch
```bash
git checkout -b <branch_name>
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
