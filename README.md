<!-- This mini Tutorial is part of a series, and created by the owner of the repository. It is not intended to be complete or have all option available, but continues improvent will occur in the future -->

<!-- This document is based on a Windows terminal, probably I will add other terminal options in the future -->

# Git mini Tutorial

Git basically is Version Control System. Although I will also mention Github, they are not the same. 

In my own words I coul say that [Git](https://git-scm.com/) is a tool an software  that you can download and install in your own computer, it helps you organice your programs, keep track of changes, and also interact with public or private services to work in a collaborative way, suc as [Github](https://github.com/).
[Github](https://github.com/) is a public service, where you can open a account and have your own repositories; it is recommended to have one repository per project; and allows others to participate.
There are many companies that offer their code on this service. Another popular alternative to Gouhub is Gitlab.

*****

## Contents
- [Git verification](#git-verification)
- [Git configuration](#git-configuration)
- [Creating a repository](#creating-a-repository)
- [Terminology](#terminology)

*****

## Git verification
Once you install Git on your local computer (in Windows is very easy, it is like any .exe application), open the _Git Bash_ terminal and verify with the single command:

```
$ git version
git version 2.28.0.windows.1
```

From the Git Bash terminal you still can use your traditional Windows commands, for example you can open the Windows explorer with:
```
$ explorer .
```
Open Visual Studio Code:
```
$ code .
```
Or listing the content of files and directories:
```
$ dir
```
But I will use more bash or linux type commands instead of the tradditional windows commands:
```
$ ls
```

*****

## Git configuration
We will explore some of the git config options, that allows to initiallice are Git configuration, and check configuration parameters if required.
```
$ 
```

*****

## Creating a repository

The first I recommend is to create a directory to store all your repositories:
```
$ mkdir GitHubRepositories
$ cd GitHubRepositories/
```
Also to open your account on Github. You can create your repository on Github first and then clone it in your computer. This is the method I will show here (adding more pictures later). One you have 
```
$ git clone https://github.com/<my_repo_name>/miniGitTutorial.git
$ cd miniGitTutorial/
(main *) miniGitTutorial
$ ls
README.md
(main *) miniGitTutorial
```

*****

## Terminology
There are many words used here that may requiere further explanation:
- Repository: each project is realted to a repository, it is the group of files related to the project.
- Local repository: usually are the files stored in your own computer
- Remote repository: refers to the files stored in a server where all users accessing the repository can have access.
- Branch: by default there is alwys at lesta one branch for each repository. The first brach is ussually named Master, it is the original bracnch. You can make copies of this branch i orer to develop new features, make some enhancemenets, etc. At some point usually these additional branches can be merged again to the main branch. Branchas allows multiple persons to work on copies of the original branch without working directly on the main branch.
- Clone:
- Fork:
- Push: local to remote.
- Pull: remote to local.
- Pull request:
