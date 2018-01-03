## Instructions
This repository has branches for each of the videos in the course. 
You can use the branch pop up menu in github to switch to a specific branch 
and take a look at the course at that stage. Or you can simply add `/tree/BRANCH_NAME` to the URL to go to the branch you want to peek at. 

## Branches
The branches are structured so that they correspond to the videos in the course. 
So, for example if I name a branch `02_03b` then that branch corresponds to the 
second chapter and the third video in that chapter. The extra letter at the end 
of the name corresponds to the state of the branch. A `b` means that this is how 
the code looks at the beginning of the video, an `e` means that is how the code looked at the end of the video.

You may find additional branches that correspond to other states, so for example,
you may see a `t`, which means this is a target branch. 
A target branch is something I use during development or updates of a course 
and it's for a branch that I'm working towards. For the purposes of taking a course,
you may ignore any additional branches. The `master` branch usually has the 
state of the project as I'm working through it and the final state of the code when I finish the course. 

## Installing
1. Make sure you have these installed
	- [node.js](http://nodejs.org/)
	- [git](http://git-scm.com/)
2. Clone this repository into your local machine using the terminal (mac) or Gitbash (PC) `> git clone CLONEURL`
3. CD to the folder `cd FOLDERNAME`
4. Run `> npm install` to install the project dependencies
5. Run `> gulp` to start live preview server
