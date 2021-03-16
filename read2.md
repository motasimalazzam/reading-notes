Version Control 

Version Control is a system that permits you to return to different version of a file or set of files by recording changes. And through it, the project can be returned to a previous version. It is divided into three sections:

1) Local Version Control: A database on the hard disk to store changes to files and projects.

2) Centralized Version Control: It requires a single server that stores changes and releases files that are made by more than one developer.

3) Distributed Version Control: Its goal is to prevent the loss of changes and projects. It creates multiple mirrored repositories and this means creating backup copies of data and placing them on the server to replace any lost information and (Git) is an example and includes the following:

a) Snapshots

b) Local Operations

c) Tracking Changes

d) Loss of Data

e) States: Files in Git can reside in three main states: committed, modified and staged. Committed: data is securely stored in a local database. Modified: file has been changed but not committed to the database. Staged: flagged a file’s changed version to be committed in the next snapshot.

Initial Customization

After installing Git on the device, certain steps must be taken to change the settings, and these steps are only performed once.
Setting up a Git Repository

1)	Importing

2)	Cloning

Workflow 

1)	Local Repository Structure

The local Git repository has three components:

•	Working Directory: The actual files reside here.

•	Index: The area used for staging.

•	Head: Points to the most recent commit.
 
2)	Saving Changes: All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

3) Tracking and Staging a New File

4) Committing a File

5) Committing All Changes

6) Pushing Changes

7) Stashing Changes: git stash command temporarily removes changes and hides them, giving you a clean working directory.
