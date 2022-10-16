# Exercise 1

1. Change your global git config, adding your name and email
2. Initialise a new git repo
3. Have a look at the .git folder created by your git init command
4. With only HTML (and optionally CSS), create a very basic webpage (do refer to last week's repo if you need to)
5. Check the status of your repo, add and commit your changes
6. Find your commit(s) id.

- If in doubt, run `git --help` or follow the git documentation here:
https://www.git-scm.com/docs

It's OK to google and to visit websites like stackoverflow.com for advice too


### Optional
- Create an alias for your git command


## Exercise 2

1. Checkout in the branch boat-drawing and rebase the branch on master, to ensure the branch has the latest changes in master applied to it

2. In the branch `boat-drawing` make the windows of the boat squared without changing the code, only by using git rebase -i

3. Make the background of the ship yellow by cherrypicking the relevant commit from the branch "new-background" using `git cherry-pick`
