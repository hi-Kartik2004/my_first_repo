Git commands used:
 git config -global user.name <your_name> // to configure for the first time in a folder
 git config -global user.email <email> // to configure email id for the first time in a folder
 git init // to initialize git
 git add . // to stage files
 git commit -m "message here" //to commit changes (make changes)
 git status // to check the file status/ git status
 git log // to check the previous git-changes/ history of that folder
 git reset <log_hash> // to reset work corresponding to the time stamp of the hash
 git rm -cache <file_name> // to remove file and keep it unstaged
 git rm <file_name> // to remove file permanently
 git stash // to move file to backstage
 git stash clean // to clean/clear backstage 
 git restore --staged <file_name> // To put staged item back to unstage/not tracking state
 git remote add origin <github_url> // To link github repository
 git push -u origin <branch_name> // Pushing or adding changed to github repository.
 git clone <github_repository_url> // to copy or take files from other github repositories
 git branch <branch_name> // to create a new branch 
 git checkout <branch_name> // to switch between branches
 git diff // to check the difference between the staged and the last commit
 git checkout -f // to restore the last commit changes
 git remote set-url origin <new_github_url> // to change github repository link
