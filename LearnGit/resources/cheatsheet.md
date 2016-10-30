# Git Command Cheat Sheet

##### Cloning your remote directory
		git clone <remote directory>

##### Checking that status of your local repository
		git status

##### Adding all modified files to staging area
                git add -A

##### Make a commit
                git commit 

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

##### Stashing away your dirty working directory
		git stash

##### Add a new remote repository on github
                git remote add <name of remote> <URL of repo on github>
##### Push changes to reote on github
                git push <remote name> <name of branch>

##### Show remote URL after name
		git remote -v 

##### Reset to last commit
                git reset --hard
