# A Guide to Git

Git is a Distributed Version Control System (or DVCS for short) that stores versions of files as snapshots each time you save changes, or "commit", a project. Git tracks changes made to files or directories and is set up to minimize the possibility of damage to files and data loss. 

Files in Git reside in three main states:
- ***Committed*** files are securely stored in a local database
- ***Modified*** files are files that have been changed but not committed to the database. 
- ***Staged*** files are files that are flagged to commit the changed version to the next snapshot

Additionally, files in a checked out, or "working" copy of a project file are either *tracked* or *untracked*
- ***Tracked*** are part of the most recent file snapshot an can be modified, unmodified or staged. 
- ***Untracked*** files were not included in the most recent snapshot and are not currently in a staging area.

If you have made changes to a file, but are not ready to commit the changes, you can use ` git stash ` command to temporarily remove them without losing the changes you have made. Reverse this action using ` git stash apply `. 

Often, teams may collaborate using remote repositories. These are versions of projects that reside online or on a network that files can be pushed to or fetched from. 

### Useful Commands

track a single file using:
````
git add filename
````

Track all files using:
````
$ git add *
````

Commit a file using
````
$ git commit -m "made change x,y,z etc"
````
where youre notes for the changes are inside the quotes

Commit all changes using
````
$ git commit -a
````
Push changes using
````
$ git push [remote-name] [branch-name]
````

