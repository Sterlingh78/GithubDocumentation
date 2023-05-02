## Git Basics

# What is Git?
Git is a version control system that keeps track of software between changes and updates.

# Why use Git? What problem does it solve?
Without git, there would be no simple way to keep track of changes in an app between updates or have any idea what a previous version contained. For example if you made a mistake and accidentally pushed the code, you can revert to a previous version instead of being stuck with the mistake forever

# What is the difference between Git and Github?
Git is the actual version control on the command line, while Github is one of many GUI hub websites that make navigating git files easier

## Git Rebase

# What is Git rebase?
rebase is a git command to move the entire branch to a new starting point on the tree. 

# What are some advantages and disadvantages of Git rebase? (At least 2 of each)
Advantages: 1. Maintains linear history of the project. 2. Removes unnecessary merges from the project, reulting in cleaner easier to follow code. Disadvantages: 1. Alters commit history, making it more difficult to track changes in a projecto over time. 2. Can introduce conflicts which can be time consuming and frustrating to resolve.

# When shouldn't you use Git rebase? Why?
If there are shared branches it is a big risk and usually creates conflicts. It is better to merge in this scenerio

## Rebase Screenshots:
# Rebase Merge:
![rebase image](/rebasemerge.png)

# Interactive Rebase:
![interactive](/interactive.png)

# When you shouldn't rebase with a remote repo
When other developers are currently working on the remote branch. Can cause major conflict issues 

## Git reset, checkout, and revert

# What is Git reset?
Allows you to move the branch to a different commit basically "resetting" the commit

# What is the difference between hard, mixed and soft?
Hard: completely removes changes in the staging area and working directory.
Mixed: Discards staging area changes but keeps working directory changes.
Soft: Removes nothing, just moves to a different commit and leaves all changes unstaged

# What is Git checkout?
Allows you to switch between branches on a repository

# What is Git revert?
Lets you create a new commit that undoes changes in a previous commit

# In what ways are these commands the same and what ways are they different?
They are the same becasue they switch commits or branches, but each do it in much different ways. Reset is a branch move, Revert undoes changes, and checkout lets you switch working branches

# When would you use reset, checkout, or revert? Why?
I would use reset to go back to a commit without erasing anything, a revert to go back and erase a commit, and a checkout to work on a different branch in the repository

## Screenshots:

# Reset:
![git reset](/reset.png)

# Checkout:
![git checkout](/feature.png)

# Commit:
![git commit](/commit.png)

# Revert:
![git revert](/revert.png)

## Git submodules

# What are Git submodules?
Submodules allow you to have a git repository within another git repository.

# When would you use a submodule?
So you can track dependencies between repositories and manage them as a single project.

# What are the advantages and disadvantages of Git submodules?
Advantages: You can track multiple relates repositories together as a single project. Disadvantages: can be very tricky to work with and add complexity to the repository
