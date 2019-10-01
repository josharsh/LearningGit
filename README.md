# Learning Git
This repository walks you through fundamentals of Git and Github.

## About
Get started with learning git and using github to version your softwares, codes and lots more. 

If you do not already have an account with [[Github](https://github.com)], please sign up.

### FLOW
We will start using Github's GUI based platform to start learning and further take it to using command line using bash. 
Here are the steps to follow.

## Fork this repository

A repository can be forked by clicking the Fork button on the top of the page listing the repository. Forking a repository creates a copy of the repository into your acccont.

## Clone the repository
### GUI: 
Go to your GitHub account, open the forked repository, click on the clone and download button.
### BASH:
Go to your Github account, open the forked repository, copy the URL. Navigate to terminal on the local machine. (Please ensure git is installed onto your system). Type in "git clone \[URL OF REPOSITORY]".git
e.g.:

```bash
git clone https://github.com/josharsh/learninggit.git
```
After cloning, we get the repository from our account to our local machine. Local machine is the apt place where you can work onto the project,change files, add/remove files. Generally, when you clone a repository to your local machine, the first step is to build the project (based on the technology/programming language used in the project). But initially we will restrict us to using plain documents to not get involved into complex codes and learn the github workflow. 

## Create a branch
After cloing, the repository can be found on your local machine. Change to the repository directory on your computer (if you are not already there). 
```
cd learninggit
```

### To create a branch: 
```
git checkout -b <add-your-new-branch-name>
```
e.g.
```
git checkout -b addmyfile
```
## Make necessary changes and commit those changes

Add those changes to the branch you just created using the `git add` command:
```
git add [file].md
```
OR
```
git add .
```

## Now commit those changes using the `git commit` command:
```
git commit -m "[Commit Message]"
```
## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <branch-name>
```
(with the name of the branch you created earlier)

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

## Now what???

Hunt for millions of projects which suit your tech-stack and start contributing. 
You can start from [[Open Source Guides](https://github.com/josharsh/OpenSourceGuides)]

#### Liked this project??? 
star it on [GitHub](https://github.com/josharsh/LearningGit).

#### For getting hands dirty on Git
Go To [Git-Scm](https://git-scm.com › book › Getting-Started-Git-Basics)

