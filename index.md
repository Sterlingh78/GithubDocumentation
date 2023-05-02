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
![rebase image](/rebase merge.png)
