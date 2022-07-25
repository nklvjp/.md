1. Check the version of Git installed
`git --verion`
2. Set the username/e-mail for just the current repository
`git config user.name "username"`
`git config user.mail "e-mail"`
3. Set the username/e-mail for every repository
`git config --global user.name "username"`
`git config --global user.mail "e-mail"`
4. Create a new directory `mkdir`
5. Initialize Git on the current folder
`git init`
6. Check the status of the Git
`git status`
7. Add python.py to the Staging Enviornment
`git add python.py`
8. Add all files in the current directory to the Staging Environment
`git add --all` or `git add -A`
9. Commit the changes to the current repository
`git commit -m "message"`
10. Check the compact version of the status for repository
`git status --short`
- ?? : Untracked files
- A : Files added to stage
- M : Modified files
- D : Deleted files
11. View the history of commits for the repository
`git log`
12. Create a new branch called *master-2*
`git branch master-2`
13. List the existing branches
`git branch`
14. Move to the *master-2* branch
`git checkout master-2`
15. Create, and move to a new branch with the name *temp-master*
`git checkout -b temp-master`
16. Merge the *temp-master* branch with the current branch (*master*)
`git merge temp-master`
17. Remove the *master-2* branch from the local repository
`git branch -d master-2`
