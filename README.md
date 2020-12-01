# Advanced Git

## Branching
* it is very rare to push to main, in industry we will typically have designated branches.
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
