# This is a list of git commands

- To switch branches

`git checkout <branch_name>`
 
 
- To create a new branch from the current branch you are on  
 
 `git checkout -b <new_branch_name>`

 
- Make a commit

`git commit -m "first commit"`
 
 
 - Stash away uncomitted changes(So you can pull from development)
 
 `git stash`
 
 
 - Bring back your stashed changes
 
 `git stash pop`
 
 
 - Pulling from development allowing git to go through each of your commit to check for any conflicts
 
 `git pull --rebase origin <the_repo_development_branch>`
 
 
 - If there are no conflicts to resolve
 
 `git rebase --continue`
 
 
 - If you feel like the rebase is not merging properly 
 
 `git rebase --abort`
 
 
 - To set up a link from your current local to remote branch(This will also push your remote)
 
 `git push --set-upstream origin <remote_branch_name>`
 
 
 - To push your current branch to remote
 
 `git push` or `git push origin <remote_branch_name>`
 
 
 - To delete a local branch  
 
 `git branch -d <branch_name>`
 
 
 - To delete a remote branch
 
 `git push --delete origin <branch_name>`
 
 
 # Some useful git stash tips
 
 https://www.freecodecamp.org/news/useful-tricks-you-might-not-know-about-git-stash-e8a9490f0a1a/
 
 # Some useful git commands if you done something wrong
 
 https://ohshitgit.com/
 
