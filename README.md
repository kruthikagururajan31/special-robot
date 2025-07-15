# Learning Git and Github


Git is used for versioning of data and information record keeping

- git init (This will initialize the project with Git and create a .git folder)
- git log (This will show the logs)
- git log --oneline (Shows all the log summary in one line)
- git status (This will show which branch and what state the data is at based on below states)

- States of files:
-- Tracked Files (modified & unmodified)
-- Untracked Files (without adding the files)
-- Staging

- Environments in Git:
-- Working (Current working directory)
-- Staging (Temporary location to store the files until commit)
-- Commit (Once the files are moved here, a new log entry is created with a hash)

- git add . / filename (This will add the files to the staging env to plan for commit)
- git commit -m "comment for commit" (This will commit the files in actions along with a comment, log entry and a hash)
- git commit --amend / -m "new commit message" / --no-edit (This is amend i.e add or make changes to the already made commit along with a new commit message via terminal command or using the editor which is opened upon amend command)
- git push (This will push the commited changes to the github repo)
- git restore . / filename (This will remove the changes made on the files)
- git restore filename -s / --staged (to restore deleted file)
- git rm -r --cached . (To remove cache data)
- git rm filename (This is delete the file but will also stage it automatically)
- git mv filename1 filename2 (This will rename the file1 to file2)


- git ignore 
-- Personal notes
-- Sestitive information
-- System files
-- Local env values 
-- Coding files like node_modules
-- Create it at the root level as .gitignore file


- git diff (This will show all the differences in files)
- git diff commitNub (This will take the commit number from the log oneline and shows the difference in the commits) 
- git rebase --interactive <branch>/<commit> (This will allow to amend the commit from one branch to another)

Git Flows: Create a new feature branch, switch to a feature branch, make changes, merge to master, delete the feature branch
- git branch (This will show all the branches in the repo)
- git branch -d NAME (This will delete the branch as long as conflicts don't exists)
- git switch -c NAME / git checkout -b NAME (This will copy the main/master branch to another named branch)
- git switch NAME / git checkout NAME (This will switch to the named branch)
- git merge <branch> (This will merge the branch specified to the current branch you're on - so development branch chages can be mergered to main by executing this command in main)
- git checkout -d NAME
- If you need to merge something to main, then you need to go to main and then merge the feature branch


Store the code somewhere temporary to work on something else?
- git stash (Store it somewhere on the side - works like a deck of card - latest one will be at the top)
- git stash list
- git stash apply
- git stash pop

- git clean -n (dry run) / -d (directories) / -f (force) - remove untracked files
- git clean -dn / -df


Create a remote of your work in GitHub Repository
- git remote add NAME URL 
- git remote add origin https://github.com/kgururaj0031/special-robot.git
- git remote -v (List and verbose the repo)
- git remove OLDNAME NEWNAME (This will rename the remote connection)
- git branch -M main
- git push -u origin main


GitHub is a platform for Git to socialize and store data.
