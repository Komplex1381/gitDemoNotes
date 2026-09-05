## Commands


```
git init						    # initializes the repo (a new git repository)
git add <filename>                  # Add specific file to the staging area
git add -A						    # Add all files not on ignore to stage
git commit -m "<msg>"			    # Commit changes with a message (inline msg)
git checkout - b <name>			    # Create a new branch
git checkout <branchName>		    # Switch to target branch
git status						    # Show the status of the working directory and staging area - HELP!
git merge <branchName>			    # integrate target branches commit history -  Merge changes from another branch

git tag -a '<semVer>' -m '<msg>'    # Make a tag - Create a new tag
git remote add origin <url>			# connect to githubAdd a remote repository
git pull origin <branchName>		# Fetches and merges changes from target remote branch - Pull changes from the remote repository
git push origin <branchName>		# Intergrates local branch into remote - Push changes to the remote repository
git push origin --tags				# Tags push seperately - Push all tags to the remote repository

git reset --hard <id>				# Send branch to target id. [soft, mixed, hard] Reset the working directory to a specific commit					
git log                             # git history of commits - Show the commit history for the current branch
git reflog                          # Show last few git commands and related ids - Show the history of all changes to the tip of branches and other references
```