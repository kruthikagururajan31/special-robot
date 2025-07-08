# Learning Git and Github


Git is used for versioning of data and information record keeping

- git init (This will initialize the project with Git and create a .git folder)
- git log (This will show the logs)
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
- git push (This will push the commited changes to the github repo)
- git restore . / filename (This will remove the changes made on the files)


- git ignore 
-- Personal notes
-- Sestitive information
-- System files
-- Local env values 
-- Coding files like node_modules
-- Create it at the root level as .gitignore file