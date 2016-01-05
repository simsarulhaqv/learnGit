# Git Command Cheat Sheet

##### Cloning your remote directory
		git clone <remote directory>

##### Checking that status of your local repository
		git status

##### Creating a new branch for you to work on
		git branch <new branch name>

##### See all branches in your remote repository
		git branch -a

##### Moving onto a branch
		
		git checkout <branch name>

##### Deleting a branch
		case 1: Delete a branch. The branch must be fully merged in its upstream
           branch
			git branch -d <branch name>
		case 2: Delete a branch irrespective of its merged status.
			git branch -D <branch name>			

##### Moving files while preserving git history
		git mv <source> <destination>
 
