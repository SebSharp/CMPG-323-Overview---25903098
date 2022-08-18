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
The .gitignore file is a plain text file where each line contains a pattern for files/directories to ignore - it lets Git know that it should ignore certain files and not track them.

This file will be placed in the root of the CMPG main repository. It is worth keeping in mind that the patterns in the files are relative to the location of that .gitignore file.

Source: <cite>https://www.pluralsight.com/guides/how-to-use-gitignore-file</cite>

## Repository Structure
A unique repository will be created for each individual project for submission purposes, except for <b>Project 1</b>, where the the existing module repository for CMPG 323 will act as its repository.

## Project Structure
The project structure, as outlined in the main module repository's milestones, will be created on a per-project basis as the semester progresses. All of these projects (1-5) will be linked to the main module repository. Each project will have it's own Insights and Boards indicating process and detailed expected completion dates for the various tasks.

### List of Current Repositories <code>(Updated Regularly)</code>
- <a href="https://github.com/SebSharp/](https://github.com/SebSharp/CMPG-323-Overview---25903098" target="_blank">CMPG 323 Repository</a> 
