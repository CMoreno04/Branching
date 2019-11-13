## GIT BRANCHING PRACTICE

### Basic 'git' commands

* 'git init' - create new local rep
* 'git add' - add current working directory to git index
* 'git commit -m "message"' - commit changes to local repo
* 'git status' - display status of local repo
* 'git branch' - Display local branches and which we are on
* 'git checkout -b newBranch' - Create and checkout branch 'newBranch'

### Merging
* add and commit local branch.
* Push local branch to remote.
* Pull 'master' from remote into local branches
'''bash
git checkout newBraanch
git pull origin master
'''
git add .
git commit -m 'merging master with newBraanch'
git push origin newBraanch
'''

* On GitHub, create Pull request
* Teammates merge Pull request  into master
