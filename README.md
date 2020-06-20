# 2020-06-16 Git

- `git init`: creates a git repository in the current directory
- `git status`: tells you want is going on
- `git add <FILENAME>`: adds the file to the staging area
- `git commit`: opens up nano, commit the file in staging with a message
- `git log`: shows the history of commits we have done 
	- `git log --oneline`: shows a shorter oneline version of `git log`
- `git diff`: compares current state to the last version of the state
	- `git diff HEAD~1 <FILE>`: compares current state from one state ago
	- `git diff <HASH> <FILE>`: compares current state from state in <HASH>
	- `git diff --staged <FILE>`: compares files in the staging area  
- `git checkout <HASH> <FILE>`: reverts the <FILE> from <HASH> back to the current stage
- `git checkout <HASH>`: reverts entire folder state to <HASH>
	- `git checkout master`: to go back to the latest work
- `HEAD`: tells you where you are looking at in the history


## Remotes
- `git remote add <name> <url>`: gives the remote URL a short NAME
- `git push <where> <what>`: e.g., `git push origin master` takes the master branch on your local computer and push it to the origin location(e.g. Github)
 

