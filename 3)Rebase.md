```bash
git clone <url>
cd <repo>
```
```bash
echo " ">a.txt
git add a.txt
git commit -m "commit in main"
git push origin main
```
```bash
git checkout -b "feature-branch"
echo " ">b.txt
git add b.txt
git commit -m "commit in feature"
git push origin feature-branch
```
```bash
git checkout main
git rebase feature-branch
git push origin main
```
