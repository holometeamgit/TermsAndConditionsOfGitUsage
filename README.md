# Terms And Conditions Of Holome Git Usage

This document describes the basic rules for using holome company’s github.

## Naming

The names of projects should very accurately reflect their essence. One company may have an application on  iOS and Android and on the web as well, so a project with the company name is a very bad name and will lead to confusion. 

Example of BAD project name:
  - ASOS
  - Nike
  - HolomeSDK

Example of GOOD project name:
  - ASOS iOS Native
  - Nike Unity Showreel
  - iOS Holome SDK


## Additional files

All projects must contain a detailed readme file and all related documentation

The readme file should contain a detailed description of the project, the installation process, all the major non-obvious points that are required to run, license, authorship, etc.
[Good readme sample](https://github.com/release-it/release-it#readme)

The documentation should fully cover the third-party developers requirements to use the project. Documentation files must be in a generally readable format (e.g. html or pdf)

## Sample Projects

Some of the projects that are 'Samples' (like SDK sample, WebAR sample, Steaming server sample, etc) should be relatively self-sufficient, so that you can easily fork and clone the project if it requireds for fast deploy for new projects

# Git

The best example of branching is using the [git flow technique](https://danielkummer.github.io/git-flow-cheatsheet/)
It’s not necessary to use exactly git flow, but everyone around you will be happy if you use approximate to this technique

For media or other lagre files please use [git lfs](https://git-lfs.github.com/)

Each major release version of the project must be move in the new branch
All important commits must have an explanatory tag. For example: 
- C#>4.0

As soon as the some versions cease to be compatible (like SDK for Unity 2018 and SDK for Unity 2019), it is necessary to discuss support for incompatible versions and/or possible forks it

A message in any commit should show changes in a short and clear way.

Example of BAD commit message:
  - Bugfix 21/10
  - Update API
  - Fix small bugs

Example of GOOD commit message:
  - Solve bug #21 (bug index in Jira)
  - Add play video button and required variables for it
  - Fixed error of video freezing at device rotation at 90 degrees
