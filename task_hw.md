### 1. On the local repository, make branches for: 
- Postman
- Jmeter
- CheckList
- Bug Report
- SQL
- Charles
- Mobile testing
#### Create the local repository ➡️ ```git init```
#### GitHub ➡️ New repository ➡️ Create repository
#### On the local repository ➡️ ```git remote add origin https://github.com/<YOUR_NAME>``` 
#### Next step ```git pull origin main```
#### Create branches:
```bash
git checkout -b postman
git checkout main
git checkout -b jmeter
git checkout main
git checkout -b checklist
git checkout main
git checkout -b bug_report
git checkout main
git checkout -b sql
git checkout main
git checkout -b charles_proxy
git checkout main
git checkout -b mobile_testing
```
### 2. Push all branches to the remote repository
```bash
git status
git add .
git commit -m "commit message"
git push
```
### 3. In the bug_report branch, create a text document with the structure of a bug report
```bash
git checkout bug_report
cat > bug_report.txt
<YOUR BUG_REPORT>
^C
```
### 4. Push the bug_report structure to the remote repository
```bash
git status
git add .
git commit -m "commit message"
git push
```
### 5. Merge bug_reports branch into main
```bash
git checkout main
git merge bug_report
```
### 6. Push main to the remote repository
```bash
git push origin main
```
### 7. In the checkList branch, create a document with structure of a checklist
```bash
git checkout checklist
cat > checklist.md
<YOUR CHECKLIST>
^C
```
### 8. Push the document to the remote repository
```bash
git status
git add .
git commit -m "commit message"
git push
```
### 9. Make a Pull Request of the checkList branch in main, on the remote repository
#### Go to the remote repository in the checkList branch ➡️ Compare&pull requset
### 10. Synchronize external and local main branches
```bash
git checkout main  
git pull origin main 
```