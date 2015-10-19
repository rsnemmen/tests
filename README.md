Learning to use Git and GitHub
=================

<img src="gitlogo.jpg" width="100px" />

This tutorial will get you trying out Github and Git. Along the way, you will learn how to collaborate in a project you are a part of.

TL;DR: how to add files to a github project and deal with merge conflicts.

# Tasks

### 1. clone the repo in your computer

```
git clone git@github.com:rsnemmen/tests.git
``` 

### 2. add a file to the repo (e.g., mariana.txt, rodrigo.txt) and upload to github

```
git add yourfile.txt
git commit -am "added my glorious file" # please write a useful short description
git push
``` 

### 3. everybody download the updated project

```
git pull 
``` 

### 4. now everybody edit random parts of file *paper.tex*

Don't forget to commit what you just did, otherwise git does not know things changed:

```
git commit -am "description of what you just did" 
``` 

### 5. upload to github

```
git push 
``` 

### 6. download updated project and deal with the merge conflicts (if any)

```
git pull 
``` 
