echo "# commands" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git remote add origin https://github.com/iPruthviRaju/commands.git
- git push -u origin master

Push an existing repository from the command line

- git remote add origin https://github.com/iPruthviRaju/commands.git
- git push -u origin master

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
