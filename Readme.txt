Git commands used:
9. git config -global user.name <your_name> // to configure for the first time in a folder
10 git config -global user.email <email> // to configure email id for the first time in a folder
1. git init // to initialize git
2. git add . // to stage files
3. git commit -m "message here" //to commit changes (make changes)
4. git status // to check the file status/ git status
5. git log // to check the previous git-changes/ history of that folder
6. git reset <log_hash> // to reset work corresponding to the time stamp of the hash
7. git rm -cache <file_name> // to remove file and keep it unstaged
7. git rm <file_name> // to remove file permanently
8. git stash // to move file to backstage
9. git stash clean // to clean/clear backstage 
8. git restore --staged <file_name> // To put staged item back to unstage/not tracking state
11. git remote add origin <github_url> // To link github repository
12. git push -u origin <branch_name> // Pushing or adding changed to github repository.
13. git clone <github_repository_url> // to copy or take files from other github repositories
14. git branch <branch_name> // to create a new branch 
15. git checkout <branch_name> // to switch between branches
16. git diff // to check the difference between the staged and the last commit
17. git checkout -f // to restore the last commit changes
18. git remote set-url origin <new_github_url> // to change github repository link
