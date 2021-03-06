---
title:  "Contributing to the SDF with Github"
date:   2018-04-01 16:16:01 -0600
categories: learning
post_importance: 3
---
# Contributing to the SDF with Github

This article will show you how to use Git and Github to fork an SDF github repo, and create a pull request to submit work to the SDF

## Sign up for github
1. Enter the website https://github.com
2. Register your account (if you have account you can omit this step)
3. Sign in to your account.

## Install git
1. [Download git](https://git-scm.com/downloads) (version depends on your OS)
2. Install git (OS dependent)
3. Before fork or clone repository you must set up your git. [Here](https://help.github.com/articles/set-up-git/)
   is a good explanation (Setting up Git chapter and the three steps below)

## Fork an SDF repo
1. Navigate to the [SFD repository](https://github.com/StratisDevelopmentFoundation)
2. Click repository StratisDevelopmentFoundation.github.io
3. Find Fork button and click it
   You have just forked the repostiory into your account

## Clone the repo locally
1. Navigate to your fork, should be like this *https://github.com/YOUR-USERNAME/StratisDevelopmentFoundation.github.io*
2. Under the repository name, click *Clone or download*.
3. You can clone repostiory by HTTPS or SSH protocol (if you prefer second option, you must first [generate SSH keys](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)
4. Open Git Bash
5. Move to your folder (use cd .., cd, ls command)
6. Use *git clone git@github.com:YOUR-USERNAME/StratisDevelopmentFoundation.github.io.git*

## Modify the repo locally

Before you start you must create your own local branch:

1. Open Git Bash
2. Move to folder ../StratisDevelopmentFoundation.github.io on your computer (use *cd .., cd, ls* command)
3. Use *git checkout -b "name_of_your_new_branch"* (you can check your current branch with *git branch*)
4. You can make changes on your repository locally right now. When you finished you can commit your changes.
   The below steps describe how.

## Commit changes to your github fork
1. Open Git Bash
2. Use *git status*. You can see the result of your changes.
3. Use *git add -A*
4. Use *git commit -m "commit_name"*
5. Use *git push origin "name_of_your_new_branch"*

## Create a pull request to the original SDF repo
1. Enter into your account on Github.com
2. Select repository *StratisDevelopmentFoundation.github.io*
3. Click *New Pull Request* button
4. Select your own branch for comparison with *base: master* SDF repository
5. Click *Create Pull Request* button
