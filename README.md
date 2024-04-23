# test_git
resp to test git commands
https://www.freecodecamp.org/news/git-push-local-branch-to-remote-how-to-publish-a-new-branch-in-git/


Here I will write down the commands I am testing in the terminal in gitpod:

Working on my own project using only one workspace, one branch:

TERMINAL:
git add .
git commit -m '...'
git push


# Push the Main Branch to Remote

Working on my own project using one workspace, multiple branches:

TERMINAL:
git init
test
test
test new branch

To push the main repo, you first have to add the remote server to Git by running git remote add <url>.

To confirm the remote has been added, run git remote -v:


# Push a new branch to remote (Github)
create a new branch:

git branch <branch-name>


Switch to the branch:

git switch branch name or git checkout <branch-name>.


Add new branch to remote (save)

git push -u origin <branch-name>
