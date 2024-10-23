Some comments added here to document our software


<!-- How to rebase and fix merge conflicts with main -->
```
git checkout main
git pull origin main
git checkout feature-branch
git rebase origin/main
git add <filename>
git rebase --continue
git push --force-with-lease origin <branch-name>
```
