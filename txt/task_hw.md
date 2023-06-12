#### 1. Create an external repository called 'txt'
```
GitHub ➡️ New repository ➡️ Create repository 
```
#### 2. Clone the 'txt' repository to a local machine
```bash
git clone <SSH key>
```
#### 3. Inside the local JSON create a 'new.txt' file
```bash
cd txt/
cat > new.txt
```
#### 4. Add changes to indexed files section
```bash
git add .
```
#### 5. Commit the file
```bash
git commit -m "commit message"
```
#### 6. Push the file to the external GitHub repository
```bash
git push
```
#### 7. Edit the content of the file 'new.txt' - write information about yourself (name, age, number of pets, future desired salary). Everything is written in txt format
```
name: Anna;
surname: Gvozdeva;
age: 31;
pets: 0;
desired salary: 100000.
```
#### 8. Push changes the an external repository
```bash
git add .
git commit -m "commit message"
git push
```
#### 9. Create a file 'preferences.txt'
```bash
cat > preferences.txt
```
#### 10. In the file 'preferences.txt', add information about your preferences (favorite movie, favorite TVshow, favorite food, favorite season, country you would like to visit). In txt format
```
favorite movie: 'Midnight in Paris';
favorite TVshow: 'The Sopranos';
favorite food: Italian cuisine;
favorite season: Spring;
country to visit: China.
```
#### 11. Create a file 'skills.txt' and add information about the skills that will be studied in the course. In txt format
```
skill 1: QA Theory;
skill 2: HTTP;
skill 3: GIT;
skill 4: Postman;
skill 5: Charles;
skill 6: DevTools;
skill 7: VPN;
skill 8: Android Studio;
skill 9: Xcode;
skill 10: Terminal;
skill 11: SQL.
```
#### 12. Send two files at once to the external repository 
```bash
git add .
git commit -m "commit message"
git push
```
#### 13. On the web interface, create a file 'bug_report.txt'
```
➡️ Add file ➡️ Create new file
```
#### 14. Press 'Commit changes', save changes on the web interface
```
➡️ Commit new file
```
#### 15. On the web interface, modify the file 'bug_report.txt' and add a file. In txt format
```
ID: 01;
Title: No notification, in the authorization form, about the successful registration of a new user;
STR: 
     1. Go to the main page of the site (link);
     2. Enter data in the  "Login" field;
     3. Enter data in the "Password" field;
     4. Press "Register";
Environment:
     OS: iOS 16.2 iPhone 12 Pro;
     Browser: Safari 16.2;
Actual result: A message appears, about successful registration;
Expected result: A user has no understanding of the registration result;
Severity: Minor;
Priority: Low;
Attachments: Link to the image or video with the bug.
```
#### 16. Press 'Commit changes' and save changes on the web interface
```
➡️ Commit changes 
```
#### 17. Synchronize the external and the local 'txt' repository
```bash
git pull
```
