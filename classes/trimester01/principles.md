---
title: Principles and practices, project management (Jan 28)
layout: lesson
---

![gitvsmercurial](./mercurial-vs-git.jpg)

## Summary

- [Introduction](#introduction)
- [Learning path](#learningpath)
- [Conclusion](#conclusion)

## Introduction
In the first class Neil spoke about principles and practices of Fablabs and about project management focusing attention in describing the software tool that could be useful for finalazing this task (distributed version control softwares).
The goal of this week are:

- start to use software for version control like Mercurial;
- set up a web site (using HTML5), where describe briefly ourself, document our Fabacademy week assignements and our final project;
- define the idea of our final project.

## Learning path
In this first assignement i follow this strategy:

1. install and explore git and mercurial with the objective of find a feeling with the techniques of file version control and explore the principal command of this kind of software.
2. finding software tools that could help me in the task of setting up a website compliant with HTML5.
3. define the idea of my final project.

### Version control
In the first time i used git to versioning my archive files because:

- it is easy to install;
- very powerfull;
- easy linkable with external service like the famous [Github](www.github.com), that allow you to publish your site in a free domain without any extra effort [GithubGeo](githubgeo.github.io);

<span style="color:red"> My experience with this versioning software was not easy at the beginning because you have to understand how this tool work and the basic command to set up the a fully functional versioning system on your archive.</span>   
On the other side this kind of softwares are very well documented and in every moment you can read the manpages to find the correct use of it.

This is the tipical workflow that i use to track my archive:

	# Set up your archive in a directory named fabacademy-geo (only the first time you set up the archive)
	git fabacademy-geo
	# After adding some files on the archives you can add all the files to the tracking system with this command
	git add --all
	# Then you have to commit these files and write a message to explain what you have done
	git commit -m 'First commit'
	# Finally you can push your files to a remote repository
	git push origin master

In Fablab Cascina we use a bash script to align all the students archive with the European Fabacademy 2015 archive. This is the script:

I tried also Mercurial to version other archives files project that i commnly use in my work. The basic workflow that i use in this case is:


### Web site

- what programs i use and why: jekyll and bootstrap
- install troubleshootings and hints for an ubuntu installation
- Structure of the program and how to use it


### Final project
Finding an idea for a project could seem an easy task but i experienced that is not so easy. The first problem that i encountered was the _"orror vacui"_ when you are in front of a blank page. I tackled this difficulties writing in this blank page: my interests, my needs, my knoledges in a form of a personal brainstorming.
![brainstormingfinalprject](./brainstorminfp.jpg)

The picture emerged from the brain storming was that the project had to be the following characteristics:

- focused on air filtering of VOC pollutant;
- estetically interesting;
- integrate the most knoledges (learned in the Fabacademy) as i can manage;
- usefull;
- expandable fuctions;
- integrate my interest in nature.

Keeping in mind all those characteristics it was easier define the project: a filter for cleaning indoor pollution that use the power of plants to filter air and the power of technology to monitor the ambient and optimize the time of work of th filter.
There is a detailed description in the [dedicated page](./finalproject/index.html) on my personal website.   

## Conclusion

Working for this first class i learned a lot of things, but in particular i was impressed from the power of softwares like git and mercurial.
<span style="color:green"> I think that using a versioning control system could save me a lot of time in managing my future projects. In fact in this way it is an easy task to track the version of the files, to branch a project for experiment new feature, to backup the data of any project using online services and finally to set up a cooperation</span>.

> In my backpack of experiences surely i will put mercurial or git. 