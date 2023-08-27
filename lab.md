Description
Source Control Management (SCM) is an essential component of any DevOps pipeline. Git is the leading source control tool, and an understanding of its functionality is useful in a variety of roles. This activity will guide you through the basics of installing git and using a git workflow. After installing and configuring git, you will make a code change, commit it, push it to a remote git repository, and merge it using a pull request.

Objectives
Successfully complete this lab by achieving the following learning objectives:

Get Git installed successfully

Git has to be installed successfully on the cloud server.

You can install git like this:

 sudo yum -y install git
 
Get your personal fork of the git repository cloned to the cloud server

You need to clone your personal fork of the sample git repository to the cloud server. Make sure you are in your home directory when performing the clone.

You can do so like this:

 cd ~/
 git clone git@github.com:&ltyour username&gt/cicd-pipeline-train-schedule-git.git
Push your commit to a new remote branch

Create a new branch, make a change in that branch, commit it, and push it to your personal fork on GitHub.com.

You can do this like so:

 git checkout -b myBranch
 <make changes to source files>
 git add .
 git commit -m "<commit message>"
 git push -u origin mybranch
 
