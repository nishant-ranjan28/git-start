## Basic Git commands

* Initialise the git in repo
> git init

* Check Status
> git status

* Add changes
> git add .
 
* Check branch
> git branch

* Commit
> git commit -m `message`

* Create branch
> git checkout -b `branch-name`

* Push your code in branch
> git push origin `branch-name`

* To create PR (Pull request)
> After push on branch, one url will be displayed on terminal. Copy and launch in browswer.

* Check your current branch
> git branch

* To start working in a different branch, use git checkout to switch branches.
> git checkout

* To connect a local repository with a remote repository.
> git remote add origin `repo link`

* To create a local working copy of an existing remote repository,
> git clone `remote_URL`

* To get the latest version of a repository run git pull.
> git pull

## Advanced git commands

* To save changes made when they’re not in a state to commit them to a repository.
> git stash

* To show the chronological commit history for a repository.
> git log

* Remove files or directories from the working index (staging area).
> git rm

* With Git, there are many configurations and settings possible.
> git config `setting` `command`

Usage: 
```
# Running git config globally
$ git config --global user.email "my@emailaddress.com"
$ git config --global user.name "Brian Kerr"

# Running git config on the current repository settings
$ git config user.email "my@emailaddress.com"
$ git config user.name "Brian Kerr"
```
