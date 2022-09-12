---
title: Git Commands
categories: [technical]
tags: [code,syntax,reference,github,git,git commands,git cmds,cheatsheet]
---

# Cheat Sheet for Git Commands 

## Objective
___


Article aimed at quick glance for all the commands for Git repository! This cheat sheet will cover only the most needed cmds / quick cmds which will be used day in and out of a programmer.

*\*\*Recommended to use the Git Bash tool to perform all the git actions. Tool can be downloaded from [git-scm](https://git-scm.com/downloads)*

## Git Config
___


To setup the git environment in the local for the first time helps faster access to the distributed repository(s) at a system level. 

##### 1. Configuring the user name
User has to provide the first name and last name that will be attached to every commits made in the repo. It is not necessary that the user name has to be same with GitHub username or any other repo's username.
```bash
git config --global user.name <username>
```
##### 2. Configuring the user identity
Allows user to specify the user email. Both user name and user email address are identifying the repositories available in the system and not associated globally or with any distributed repos.  
```bash
git config --global user.email <userid@domain.com>
```
##### 3. Configuring the editor
To set the default editor by the git needs to be configured in the .git. This will allow git to open the editor configured for any further input required. Many editors are available like VS Code, Atom, Vim, Nano, emacs, Sublime. Here the sample is provided for VS Code.
```bash
git config --global core.editor "code --wait"
```
##### 4. To open the config file
At any point if the configuration needs to be modified, then the following command will be useful to open the config file in the editor configured.
```bash
git config --global -e
```
##### 5. Configuring the carriage return / new line
To avoid changing the status of all the files as modified because of automatic EOL conversion done.
\
Windows

```bash
git config --global core.autocrlf true
```

OS X

```bash
git config --global core.autocrlf input
```
*Without the `--global` flag, all the git configs will be applied to the specific repository only.*

## Git Online Repo
___

To start with the existing code base from the online repository say GitHub, the repo needs to be pulled to the local base. Following commands will help start the process.

##### 1. Git Fetch
To fetch or to connect to the repo available online, first the repository needs to be cloned to the local system. Steps to be followed as below: 
\
Login to GitHub and goto the repository
\
![Git-Clone](/assets/images/gitClone.PNG)
\
##### 2. Git Clone
Using the url obtained as mentioned in previous step, clone the repo using the following cmd.
```bash 
git clone https://<giturl>
```

##### 3. Git file list
To see the list of files in the directory cloned and to confirm / verify the number the files using the cmd.
```bash
ls
```

##### 4. Git Pull
On demand if the online repository is been updated by the fellow team and in order to fetch the recent changes in the directory use this cmd.
```bash
git pull
```

##### 5. Git View
To view the content inside the file 
```bash
cat <test.txt>
```  