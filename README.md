# What is the use of Github.


git is a open source commmand line version control system
So, Git is a version control system,  When developers create something (an app, for example), they make constant changes to the code, releasing new versions up to and after the first official (non-beta) release

Version control systems keep these revisions straight, storing the modifications in a central repository. This allows developers to easily collaborate, as they can download a new version of the software, make changes, and upload the newest revision. Every developer can see these new changes, download them, and contribute.

so GitHub is a website and service that provide all these services.


# Private repo Vs Public repo

## Private repo: 
 A private repo is in which the owner can choose who can see or commit to this repositry.

## Public repo:
In a public repo Anyone on the internet can see this repository. You choose who can commit.

# To clone a repo:
git clone http url

 # To create Branch:
git branch (branch name)

# How to commit:
git commit <message>

git branch -M main

git remote add origin https://github.com/ashwani100596/task.git

git push -u origin main


# How to change commit messages

git commit --amend -m "update message"

git pull

git push

# What is git stash:
Git stash is a built-in command with the distributed Version control tool in Git that locally stores all the most recent changes in a workspace and resets the state of the workspace to the prior commit state. A user can retrieve all files put into the stash with the git stash pop and git stash apply commands.

# How to get back stashed content:
To make this simple, you have two options to reapply your stash: git stash pop - Restore back to the saved state, but it deletes the stash from the temporary storage. git stash apply - Restore back to the saved state and leaves the stash list for possible later reuse. You can read in more detail about git stashes in this article.

# What is origin:
In Git, "origin" is a shorthand name for the remote repository that a project was originally cloned from. More precisely, it is used instead of that original repository's URL - and thereby makes referencing much easier. Note that origin is by no means a "magical" name, but just a standard convention.

# How to merge:
git merge desired_branch_to_merge

# How to resolve conflict
git commit -m "Merged master fixed conflict."

# What is pull request:
A Pull Request is a Git feature used to present changes made on independent branches for review by collaborators before being merged into the main project. Select the branch you created from the list. This will display the changes you made compared with the original content on the master branch.

# What are tags:
Git supports two types of tags: lightweight and annotated. 

## lightweight tag:
It is very much like a branch that doesn’t change — it’s just a pointer to a specific commit.


## Annotated tags:
They are stored as full objects in the Git database.