#Git Commands Guide
1. Initialization
Initialize a Git Repository: This command creates a new Git repository in the current directory.
Command: git init
2. Configuration
Set Global Username: This command sets your global username for Git commits.
Command: git config --global user.name "divya"
Set Global User Email: This command sets your global email address for Git commits.
Command: git config --global user.email "divyakaladharannair@gmail.com"
3. Repository Status
Check the Status of the Repository: This command shows the state of the working directory and staging area.
Command: git status
4. File Operations
Add Files to Staging Area: This command adds a specific file or all files to the staging area for the next commit.

Command: git add <filename>
Command: git add . # Add all files
Remove a File from Staging Area: This command removes a specific file from the staging area.

Command: git rm --cached <filename>
Restore a Deleted or Modified File: This command restores a deleted or modified file to its last committed state.

Command: git restore <filename>
Command: git restore --staged <filename> # From staging area
Delete a File from Repository: This command deletes a file both locally and from the Git repository.

Command: rm <filename> # Delete locally
Command: git rm <filename> # Delete and track in Git
Command: git commit -m "Deleted <filename>"
5. Committing Changes
Commit Changes: This command records the changes in the staging area to the repository.
Command: git commit -m "Commit message"
6. Branch Management
Create a New Branch: This command creates a new branch and switches to it.

Command: git checkout -b <branch-name>
Switch Between Branches: This command switches to the specified branch.

Command: git checkout <branch-name>
List All Branches: This command lists all branches in the repository.

Command: git branch
7. Viewing History
View Commit History: This command displays the commit history for the repository.
Command: git log
Command: git log --oneline # Condensed view
8. Merging Changes
Merge Changes from Another Branch: This command merges changes from a specified branch into the current branch.
Command: git merge <branch-name>
9. Remote Operations
Push Changes to Remote Repository: This command pushes the committed changes to the specified remote branch.

Command: git push origin <branch-name>
Pull Changes from Remote Repository: This command fetches and merges changes from the specified remote branch.

Command: git pull origin <branch-name>
Add Remote Repository: This command adds a new remote repository with the specified URL.

Command: git remote add origin <repository-url>
View Remote Repositories: This command lists all remote repositories configured for the local repository.

Command: git remote -v
10. Command History
Check Command History: This command shows the history of commands executed in the terminal.
Command: history
