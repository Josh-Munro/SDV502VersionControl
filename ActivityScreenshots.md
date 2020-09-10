***************************** CHERRY PICK ******************************
Cherry pick is designed to for the users to pick a commit from a branch and using it for another bracnk. Thus the term 'Cherry Picking'.
Examples of cherry picking git commands

git cherry-pick master

Apply the change from the master branch and create another commit with this code from the master.

git cherry-pick ..master
git cherry-pick ^HEAD master

These git commands allow the 

***************************** Unstaging ********************************
Unstaging is used to remove any staged files or specific commits. This can be useful for sperating commits into different files.

***************************** Unmodifying ******************************

***************************** Undoing **********************************
Undoing is helpful to find a way to undo you work, in a scenario you may of forgotten to check to add a file or rename a file incorrectly.
An example of unoding your commits is  ($ git commit --amend) 

**************************** Rebasing *********************************
There are two ways to insert changes from one branch into another branch, there is merging and rebasing. 
With mergin you merge two different commits from different branches together. However, with git rebase you are able to apply the changes from one branch and apply it directly to the other commit and branch. Its like replaying the commit into another branch, rather than merging two commits/branches together

*************************** Stashing **********************************
Git stash allows the develop to record the state of their last directory. While they want to enter in a new clean directory. Git stash command saves your local changes while reverting back to the directroy with the head commit.
You can view the stashed modifications wit this git command $ git stash list