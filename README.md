# pyStudyGroupSlack

## About us
[Join us](https://pystudygroup.slack.com) on slack!

pyStudyGroup is a python user group located on slack in which members can:
 * Ask for help
 * Share code and ideas
 * Plan and create projects as teams

This repository is for pyStudyGroup members to introduce ourselves as well as share small pieces of code with other users

## Getting started with git

Before getting started make sure you have installed [git](https://git-scm.com) on your system
and that you have a [github](https:github.com) account

### Fork pyStudyGroupSlack
To get started we must fork this project. Forking another user's project creates a copy in your own repository 
which you may edit and later send changes back to the original project.
  
To fork this project simply click on fork in the top right-hand corner of this page

### Clone pyStudyGroupSlack
A clone is copy of your git project located on your computer.
This is where we edit files in the project.

To create a clone run the following code, replacing \<user\> with your github username

```
$ git clone https://github.com/<user>/pyStudyGroupSlack.git .
```

Then go inside the pyStudyGroupSlack directory

```
$ cd pyStudyGroupSlack
```

### Create *your* directory
While inside pyStudyGroup, create a directory with your slack username
```
$ mkdir <username>
$ git add <username>
```
and go inside that directory

```
$ cd <username>
```

And there you can do what ever you want, this is your personal folder in our git project!
This is a great place to save and share code with other users

For this example I will create a README.md file
saying some things about me

```
$ vim README.md
```

I can create a folder with my projects
**OR**
Ask for help from other members

Then you go up on folder

```
$ cd ..
```

Then you add the folder on git

```
$ git add iakovos.belonias
```

Then you commit and as a commit message you write your slack name

```
$ git commit -m "iakovos.belonias"
```

And you push the commit

```
$ git push
```

If you read so far you are awesome :)
