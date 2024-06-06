# github-tutorial
This repository aims to give you more experience with working collaboratively as developeres in a repository. In this tutorial we will do the following things:
- Create a new branch and make changes by adding a file
- Within your branch, create a pull request where someone will review your code to see if it looks good.
- Merge your branch back into main
- Once everyone's changes are in main, we want to merge all the individual branches with the changes in main 
- Pair up with someone and each of you will edit the same line of code in the same file (in your own respective branches), simulating a merge conflict.
- One person will have to make a pull request to main but the other person will have to fix the merge conflict

## 1. Creating a branch and making changes
When you want to make changes to a repository, it is best practice to make a new branch from main. Use this command to create a new branch from the current branch you are in `git checkout -b branch-name`. You can check which branch you are in with `git status`. If you have made changes, you can see by doing git status and red lines appear. You have to commit all these changes and then push them to your branch. You can do this using `git add .` and then `git commit -am "your commit message here" and then finally `git push`. If you want to change branches you can do `git checkout branch-name`
## 2. Creating a pull request
Once you have made changes in your repository, you want to make a pull request back into the main branch so that everyone can see the changes. You can do this in the repo's website and making a pull request. You should comment all the changes you have make in your branch and have someone review and approve it
## 3. Pulling changes
When someone makes a push to any branch, your own github does not know that there are changes. You may see a "pull changes" when you do git status. To pull changes you can do `git pull`

## 4. Merge changes back into your own branch
If you are currently in your own branch, you can merge any branch into your branch by doing `git merge branch-to-be-merged-name-here`

