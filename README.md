# Git_Hub_HW2
**1.On the local repository, make branches for:**
   * ***Postman***
   * ***Jmeter***
   * ***Checklists***
   * ***bug_report***
   * ***SQL***
   * ***Charles***
   * ***mobile testing***
 ######
    git branch Postman
    git branch Jmeter
    git branch Chekliists 
    git branch bug_report
    git branch SQL
    git branch Charles
    git branch mobile testing
    
2. **Push all branches to an external repository**
######
    git origin -u Postman
    git origin -u Jmeter
    git origin -u Cheklists
    git origin -u bug_report
    git origin -u SQL
    git origin -u Charles
    git origin -u mobile testing
  
  3. **In the *Bug Reports* branch, make a text document with the structure of a bug report**
 ######
    git checkout bug_report
    cat >bug_report
    write bug_report strukture
    
 4. **Push the bug report structure to an external repository**
######
    git add .
    git commit -m "bug"
    git push
 5. **Merge the *Bug Reports* branch into *Main***
######
    git checkout main
    git merge bug_report

6. **Push *main* to external repository**
######
    git push
    
7.  **In the *CheckLists* branch, write the structure of the checklist**
######
    git checkout Cheklists
    cat >cheklists
 
 8. **Push structure to external repository**
 ######
    git add .
    git commit -m "bug2"
    git push
 
 9. **On an external repository, make a Pull Request of the CheckLists branch in main**
 ######
    Compare & pull request
    Create pull request
    Merge pull request 
    Confirm merge
    
 10. **Synchronize *External* and *Local branches* main**
 ######
    git checkout
    git pull
    
