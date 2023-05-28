# Contributing to the Materials for Health Lab Website

## Introductory Links
- Video intro to GitHub [https://www.youtube.com/watch?v=w3jLJU7DT5E](https://www.youtube.com/watch?v=w3jLJU7DT5E)
- Training for GitHub online [https://github.com/skills/introduction-to-github](https://github.com/skills/introduction-to-github)

## Setting up

1.	Setup GitHub account (if you haven’t one already)
2.	Setup git on your computer
    you can use a software with GUI, for example smartgit, github desktop, VS code, etc.
    you can use git from the command line, but it is more difficult (using GUI is easier because you can visualise commits, branches, etc.
3.	 Fork [https://github.com/materialsforhealthlab/materialsforhealthlab.github.io on github](https://github.com/materialsforhealthlab/materialsforhealthlab.github.io) on github
    github documentation on what ‘fork’ means [https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks)
4.	Clone your fork from GitHub, which means that you download your local copy of the website to your computer.
5.	Setting “origin” and “upstream” repositories on your computer
    What does “origin” and “upstream” mean?
        “Origin” refers to your own version of the website on Github, on which you have write permission.
        “Upstream” refers to the official repository, used to publish the website. By default, you don’t have ‘write permission’ to this repository and you need to make a “pull request” to ask your changes to be pulled and merged into the official repository.
    “origin” and “upstream” need to be setup to be able to:
        Pull latest version of the official website from “upstream”.
		Push your local change to your own version of the website on GitHub (your fork)
	See specific documentation of the software you are using; this can be done by adding a “remote” to your local git repository, you will need to have two “remote” (“origin” and “upstream”) to make pull and push easy.	
		See website	[https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork)
		
Note: It is possible to made small, typographical edits directly online on GitHub and commits the change directly on GitHub, but it is difficult to more than that.

## How to make changes to the website? 

1.	Update your local repository with the latest changes from the official repository: “pull from upstream”.
2.	Create a new branch that will be dedicated to the changes you want to be made (not strictly necessary but good practise)
3.	Make some changes to the source code and commits your changes using git or software that you set up to manage git (smartgit, github desktop, vscode, etc.)
	Try to make self-contained commits, so that it is easy to follow the history and to understand the intend of your changes. Small, self-contain and incremental changes are easy to follow in comparison to large changes in a single commit
4.	Using your git software, push your branch to your origin
5.	On GitHub, Make a “pull request” to upstream (official repository)
	In the pull request, there will some link to preview the website
6.	Your “pull request” will be reviewed.
7.	Once everyone is happy with the changes, it will be merged and automatically published online (see video again [https://www.youtube.com/watch?v=w3jLJU7DT5E](https://www.youtube.com/watch?v=w3jLJU7DT5E))


