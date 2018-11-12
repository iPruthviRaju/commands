echo "# commands" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git remote add origin https://github.com/iPruthviRaju/commands.git
- git push -u origin master

Push an existing repository from the command line

- git remote add origin https://github.com/iPruthviRaju/commands.git
- git push -u origin master

Create branch from master.
- git checkout master
- git pull
- git checkout -b new-branch1
- git push --set-upstream origin new-branch1

Merge master to feature/v1 branch
- git checkout feature/v1
- git merge master

Go to a particular commit of a git repository
- git reset --hard 552bd13a

Revert back to current commit.
- git reset HEAD@{1}

Undo last commit.
- git reset HEAD~

Push all changes to repo:
- git add .
- git commit -m "First implementation on new project"
- git push origin feature/v1

Pull hard from remote branch / Reset local repository branch to be just like remote repository HEAD
- git fetch origin
- git reset --hard origin/master

Rebase
- git pull origin master
- git checkout feature/v1
- git rebase --onto master
- git push -f origin feature/v1
