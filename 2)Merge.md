 ```bash
git clone <url>
cd <repo>
git checkout -b "feature-branch"
echo " ">a.txt
echo " ">b.txt
git add .
git commit -m "done"
git checkout main
git merge feature-branch
```
 ```bash
git stash
```
```bash
git checkout feature-branch
```
```bash
git stash apply
```
