# git-basic-exercises

# Your initial commit
 1. mkdir git-basic-exercises
 2. cd git-basic-exercises
 3. ls -a
 4. git init ||  ls -a
 5. git status
 6. touch ReadMe.md || ls -a || git status
 7. git log
 8. git add ReadMe.md
 9. git status
 10. git rm --cached ReadMe.md || git status
 11. git add ReadMe.md || git status || git commit -m "initial commit"
 12. git log

# more commits!
 1. nano ReadMe.md
 2. cat ReadMe.md
 3. git status
 4. git add ReadMe.md || git commit -m "second commit"
 5. nano ReadMe.md || git add ReadMe.md || git commit -m "third commit"

# check this out
 1. git log
 2. git checkout c6f7646ee776bccb6c4b990d82521c27cb653721
 3. cat ReadMe.md
 4. git checkout master 
 5. cat ReadMe.md

# branching
 1. git branch
 2. git branch milkshake-flavours
 3. git branch
 4. git branch || git checkout milkshake-flavours
 5. nano milkshakes.md
 6. git status || nothing added to commit but untracked files present
 7. git add milkshakes || git commit -m “added initial flavours” 
 8. git log
 9. git checkout master
 10. git log
 11.  i am really struggling with this one hey
 12. git add history.txt || git commit -m "added history"
 13. git checkout milkshake-flavours || git log
 14. nano ReadMe.md 
 15. git checkout History || cat ReadMe.md
 16. echo booya >> ReadMe.md 
 17. git add ReadMe.md || git commit ReadMe.md -m "rewrote ReadMe"
 18. git checkout master

# merging
 1. git merge milkshake-flavours
 2. git checkout History || git merge master
 3. git checkout master || git log

# GitHub
     
