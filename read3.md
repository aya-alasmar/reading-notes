### Git Tutorial 
#### Version Control
it's like a history of your changes , you can observe the various versions you made it on the project or file , and you can go back to any old version you need By **Version Control System (VCS)**. 

##### Local Version Control
A Local VCS entails one database on your hard disk that stores changes to files.

##### Centralized Version Control (CVCS)
This system entails a single server storing all changes and file versions, which can be accessed by various clients.

##### Distributed Version Control (DVCS)
allows clients to create mirrored repositories.These data backups can be easily be placed on the server to replace any lost information.

###### what is Git? 
* Git is a DVCS that stores data in a file system made up of **snapshots**, every * commit * you did it that's called a snapshot stored in the system , and you can go back to any version or changes you did on the project . Every single change applied to any file or directory is tracked by Git. 
* Files in Git can reside in three main states:
     1. **Committed** Data is securely stored in a local database.
     2. **Modified**  File has been changed but not committed to the database.
     3. **Staged** Flagged a file’s changed version to be committed in the next snapshot.

###### Workflow :
* The local Git repository has three components:
     1. Working Directory: The actual files reside here.
     2. Index: The area used for staging
     3. Head: Points to the most recent commit

![workflow](workflow.png)

* **Saving Changes** :
     1. **Tracked** files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
     2. **Untracked** files were not in the last snapshot and do not currently reside in the staging area.
* After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.
* **The Life Cycle of File Status**:
     1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
     2. You stage the modified file.
     3. Then, you commit staged changes.
* **command** :
     * `git status ` : To determine the state of files.
     * `git add filename`: To track one file only.
     * `git add *` :To track all files in a repository .
     * `git commit -m “made change x,y,z” `: Committing a File (After staging , you should commit the changes and record what you did within the commit message)
     * `git commit -a` :Committing All Changes.
     * `git push origin master` :Pushing Changes (from the local “master” branch to the remote repository named “origin”).
     * `git stash `: Stashing Changes (When you are not ready to commit changes but do not want to lose them either)
     * `git stash apply` : Retrieve the hidden changes.

* **Remote Repositories** : You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.
     * Cloned Repositories :Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.





