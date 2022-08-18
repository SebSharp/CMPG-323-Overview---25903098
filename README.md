# CMPG-323-Overview---25903098
Module Content Repository for CMPG 323 2022

## Branching Strategies
The branching strategy I will be using is <tt>GitFlow</tt>

GitFlow might be more complex and advanced for most modern projects, however it enables parallel development allowing for developers to work separately from the master branch on features where a feature branch is created from the master branch.

The moment changes are completed, developers then merge the changes into the master branch for release.

This strategy consists of the following branches:

-Master 
-Develop
-Feature- to develop new features that branches off the develop branch 
-Release- help prepare a new production release; usually branched from the develop branch and must be merged back to both develop and master
-Hotfix- also helps prepare for a release but unlike release branches, hotfix branches arise from a bug that has been discovered and must be resolved; it enables developers to keep working on their own changes on the develop branch while the bug is being fixed.

The main and develop branches are considered to be the main branches, with an infinite lifetime, while the rest are supporting branches that are meant to aid parallel development among developers, usually short-lived.

## Project & Repository Structure

### List of Repositories
- <a href="https://github.com/SebSharp/](https://github.com/SebSharp/CMPG-323-Overview---25903098" target="_blank">CMPG 323 Repository</a> 
