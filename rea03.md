# Version Control

Version Control is a system that allows you to revisit various versions of a file or set of files 

by recording changes

# Distributed Version Control
DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

# git

Git is a DVCS that stores data in a file system made up of snapshot

# States

Files in Git can reside in three main states: committed, modified and staged.

Committed

Data is securely stored in a local database

Modified

File has been changed but not committed to the databas


# The local Git repository has three components:

Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit

When you are not ready to commit changes but do not want to lose them either, 
git stash is a great option. This command temporarily removes changes and hides them, 
giving you a clean working directory. When you are ready to continue working on the changes, 
simply use the git stash apply command to retrieve the hidden changes..


