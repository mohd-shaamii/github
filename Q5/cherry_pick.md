```bash
git clone <url>
cd <repo>
```
```bash
git checkout -b "source-branch"
```
```bash
echo " ">a.txt
git add a.txt
git commit -m "first commit"
```
Do it 3 times a,b,c files
```bash
git push origin source-branch
```
```bash
git checkout main
```
```bash
git cherry-pick source-branch~2..source-branch
```
```bash
git push origin main
```
