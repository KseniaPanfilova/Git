# Git

Here are git commands that I've mastered and can use in my work.

The document is built on the principle of task - answer.

**1. Create following branches in the local repository:**
- Postman
- Jmeter
- Check Lists
- Bug Reports
- SQL
- Charles
- Mobile Testing
```sh
git branch "Postman"; git branch "Jmeter"; git branch "CheckLists"; git branch "Bug_Reports"; git branch "SQL"; git branch "Charles"; git branch "Mobile_testing"
```

**2. Push all branches to the external repository**
```sh
git push -u origin "Postman"; git push -u origin "Jmeter"; git push -u origin "CheckLists"; git push -u origin "Bug_Reports"; git push -u origin "SQL"; git push -u origin "Charles"; git push -u origin "Mobile_testing"
```

**3. Create a text document with the bug report structure in the Bug Reports branch**
```sh
git checkout Bug_Reports
touch Bug_report_structure.txt
```

**4. Push the document with the bug report structure to the external repository**
```sh
git add Bug_report_structure.txt
git commit -m "Adding Bug_report_structure.txt"
git push
```

**5. Merge the Bug Reports branch into the Main brunch**
```sh
git checkout main
git merge Bug_Reports
```

**6. Push the Main brunch to the external repository**
```sh
git add Bug_report_structure.txt
git commit -m "merege Bug Reports"
git push
```

**7. Create a text document with Check list structure in the CheckList brunch**
```sh
git checkout CheckLists
touch Check_list_structure.txt
```

**8. Push the document with Check list structure to the external repository**
```sh
git add Check_list_structure.txt
git commit -m "Add Check_list_structure.txt"
git push
```

**9. Make Pull Request of the CheckList brunch into the Main brunch in the external repository**
```sh
Pull request > Compare and pull request > Create pull request > Merge pull request > Confirm merge
```

**10.Synchronize External and Local Main branches**
```sh
git checkout main
git fetch
git pull
```
