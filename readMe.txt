GIT: AS SOON AS you initialize a folder as a GitHub repository anything inside of it is going to 
be tracked by git, meaning you can add files and use git commands within this folder

Initialize a new git repository: 				git init 
If you want file/changes to NEXT commit:  			git add readMe.txt 
If you want to check what you have just done: 		git status
After you have staged you can commit with:			git commit -m "short desc. Of changes"
If you want to add everything in the repository:		git commit .
Want to create another branch copies current branch: 	git checkout -b newBranchName
Switch back to master branch/other:			git checkout master
Merge changes from one branch to another:			git merge master
Add remote to repository example to push/pull update:	git remote add origin https://github.com/ChrisrunnerR/test_.git
Above says you're adding a remote repository called ORIGIN that has that url. 

Push all of our commits to the remote origin repository	git push -u origin master


Allow us to attach an email/username to access reposity both of these steps should only be like 1 time ( for push/ pulling remote repository )

Allows us to work with a remote repository pick username	git config --global user.name "CptCrunch"
	
Allows us to attach email to our username 			git config --global user.email "email"

