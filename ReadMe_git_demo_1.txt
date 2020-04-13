Post making the changes to ReadMe_git_demo.txt file we did the following to push the changes to github remote repository 'https://github.com/sonalimajumdar80/git_demo':
step 1: $ git status
The above command on execution, provides the status of changes made to the directory but not yet included into the stage area / tree from where it can be committed to the local repository and then to the remote repository.

step 2: $ git add <filename> // adds a specific file to the stage area
	$ git add * 	     // adds all the files present in the current directory to the stage area.

step 3: $ git commit -m <comment>
The above command commits the objects/files present in the stage area to the local repository which was cloned and created in the desktop from the remote repository.

step 4: $ git push
The above command pushes the changes done to the local repo to remote repo ( here, since we are working on the master branch, hence commit is pushed to master branch only.)
