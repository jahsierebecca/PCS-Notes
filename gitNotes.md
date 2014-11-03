##Questions
* How/why does github exist for free?
* Are we going to cover more sass stuff?

##Terminal Commands

* **cd** - think 'change directory:' change the current working directory. Remember that ~ is a special symbol that always represents your "home" directory.
* **ls** - think 'list:' shows a list of all files/folders in the current directory. With the -a flag, also shows hidden files and folders.
* **mkdir** - think 'make directory:' creates a new directory with the specified name.
* **touch** - updates the "last modified" timestamp on a file to now. Also creates an empty file if the filename specified doesn't exist.
* **mv** - think 'move:' moves a file or directory to a new location. This also makes it a convenient way to rename files and folders.
* **rm** - think 'remove:' deletes the file(s)/folder(s) specified.

##Git Gommands

* Use **git --version** to find out if Git is installed
* **git config** - allows you to make configuration changes to Git. With the --global flag, makes these changes available across your entire system.
* **git init** git init [projectName] - initializes a new repository. If projectName is provided, it creates a new project directory with that name. If not, it initializes a repository in the current directory.
* **git add** - adds files to the repository so that Git knows to track their changes.
* **git commit** - commits all added files to the repository as a change. With the -a flag, commits all changes to all tracked files. With the -m flag, allows you to specify a commit message directly on the command line instead of in your default editor.
* **git status** - show the current status of the git repository, including if there are ay uncommitted changes and whether or not any of our changes have been put in the staging area.
* **git log** - Show us a chronological log of all of our commits to the current repository.
* **git checkout** - "check out" a different version of the code from the one you're currently looking at
* **git diff** - create a "diff" view to demonstrate what has changed between two different versions of your repository.
* **git branch branchname** create a new branch named branchname.
**When switching branches you switch repositories.
* **git checkout branchname** - switch to the branch named branchname.
* **git checkout -b branchname** - create a new branch named branchname and switch to that branch.
* **git branch** - list all branches in the current repository and indicate which branch you're currently in.
* **git branch -D branchname** - delete the branch named branchname from the repository.
* **git merge branchname** - merge the history from branchname into the current branch.
* **git clone** - create a new repository that is a clone of a remote repository.
** git clone www.fflksdalkjf…. (url of repo)
* **git remote** - list all remote repositories associated with the current repository.
* **git remote add** - add a new remote repository to the current repository.
** git remote add nameremote url of clone
* **git push** - push your latest changes to a remote repository.
* **git pull** - pull the latest changes from a remote repository to your repository.
* **origin** - the name of the first clone.
* **HEAD** what branch you are on and what commit
* **git merge --abort** Aborts merges
