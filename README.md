# SDV502VersionControl
Version contorl github activity

<br />

### Git Cherry-Pick:<br /> 
Git cherry-pick applies changes made some existing commits.

```markdown
gut cherry-pick
```
<br />

</p>
<p align="center"> 
<img src="images/git-cherry-pick.png" />
</p>

<br />

### Unstaging:<br /> 
How to unstage files using git..
<br />
Some commands that are useful are..
<br />

```markdown
git reset HEAD <file>
```
This removes files from staging, HEAD is the last commit of the branch.
this keeps the file but keeps the modifications.
<br />

```markdown
git checkout -- <file>
```
Revert the file back to state before changes were made 

<br />

```markdown 
git rm `*.txt`<br />
git rm -r <directory name>
```
To remove a file from disk and repo use git rm, to remove a directory use the -r flag.

<br />

```markdown
git rm <filename> --cache
```
If we want to remove a file from the repository but keep it on disk, If you forgot to add it to your .gitignore file then use --cache

<br />





