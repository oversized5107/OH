# Create a new branch
```
git branch new-branch
```

# Switch to a different branch
```
git checkout branch-name
git switch branch-name     (recommend)
```

# Merge changes from branch-name into now
```
git merge branch-name
```

# Delete a branch
```
git branch -d branch-name       (unbranch)
git branch -D branch-name       (force)
```

```
git checkout --orphan new_initial_branch
# git add -A
git commit -m "update"
git branch -D main
git branch -m main
git push -f origin main
```