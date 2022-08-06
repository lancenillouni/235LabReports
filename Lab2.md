# Compsci 235 Lance Nillo Lab 2 Report

## Notes

### Git Basic Commands

- **Git Status**
  - Checks the current working tree status (locally)
- **Git Pull**
  - Fetches update from remote
- **Git Add and Commit**
  - git add [filename] selects that file, and moves it to the staging area, marking it for inclusion in the next commit. You can select all files, a directory, specific files, or even specific parts of a file for staging and commit.
  - The commit command performs a commit, and the -m "message" adds a message.
  - Adding commits keep track of our progress and changes as we work. Git considers each commit change point or "save point". It is a point in the project you can go back to if you find a bug, or want to make a change. When we commit, we should always include a message.

## Reflection
Through this lab I have had practical experience with git/github and using it with PyCharm. I now understand how to set up git repo and commit files. I can see how it is used in a practical sense in projects as a very effective version control system and is something I am excited to use in the future.

## Exercise Answers

1. In a scenario, where you work with others as a team. You wrote some code 
using the lab machine, but the code isn't working. You decide to continue 
working on the code from home. What's the best way to commit your unfinished code
to GitHub without interrupt others? What commands do you need to achieve that?

- You would want to create a branch based on the master branch. This enables you to do all development and testing in an isolated space. This allows other people to make changes in the master branch or their feature branches. Once you are finished with your work you can merge it to master branch. 
- Commands needed are 
  - git branch <"branch name">
  - git checkout <"branch name">
  - git checkout main
  - git merge <"branch name">
  - git push origin main
  - git branch -d <"branch name">

2. Explain the difference between merge and fork. Give an example for each use 
case.
- ## Git Merge
  - This is the process of combining different changes in code from different branches, or different versions of the same branch.
  - For example, if someone has completed work in a branch, they may merge it to the master branch. If there are no conflicts, then the master branch will have all the new changes implemented.
- ## Git Fork
  - This allows users to fork a repo, meaning they make a local copy in their Git repo account. 
  - A use case for this is someone forking a Git repository, making changes and then when finished sending a pull request to get the code accepted into the main repoistory.