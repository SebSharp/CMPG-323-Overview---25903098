# CMPG-323-Overview---25903098
Module Content Repository for CMPG 323 2022

## Branching Strategy
The branching strategy I will be using is <tt>GitFlow</tt>

GitFlow might be more complex and advanced for most modern projects, however it enables parallel development allowing for developers to work separately from the master branch on features where a feature branch is created from the master branch.

The moment changes are completed, developers then merge the changes into the master branch for release.

This strategy consists of the following branches:

- Master 
- Develop
- Feature: Features that branches off the develop branch 
- Release: Help prepare a new production release
- Hotfix: Branches arise from a bug that has been discovered and must be resolved

<img src="https://www.flagship.io/wp-content/uploads/gitflow-branching-strategy.png" alt="">

The main and develop branches are considered to be the main branches, with an infinite lifetime, while the rest are supporting branches that are meant to aid parallel development among developers, usually short-lived.

Source: <cite>https://www.flagship.io/git-branching-strategies/#:~:text=A%20branching%20strategy%2C%20therefore%2C%20is,interact%20with%20a%20shared%20codebase.</cite>

## Project <tt>.gitignore</tt> File
The .gitignore file is a plain text file where each line contains a pattern for files/directories to ignore. 

Generally, this is placed in the root folder of the repository, and that's what I recommend. However, you can put it in any folder in the repository and you can also have multiple .gitignore files. The patterns in the files are relative to the location of that .gitignore file.

## Project & Repository Structure

### List of Repositories
- <a href="https://github.com/SebSharp/](https://github.com/SebSharp/CMPG-323-Overview---25903098" target="_blank">CMPG 323 Repository</a> 
