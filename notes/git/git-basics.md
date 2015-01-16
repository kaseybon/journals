#Gitting Started

##Contents

1. Terminology
1. Commands
1. How To's
1. Learn More

##Terminology

**Git** - A distributed version control system that creates snapshots (commits) of a project. Records changes to a project that you can recall at a later time.

**HEAD** - A project's most resent snapshot.

**Branch** - An independent line of development in a project.

**Master** - A project's default development branch.

**Repository** - A collection of commits and branches.

**Staging Area** - Holds changes that are ready to be committed.

##Commands

**git add** - Moves changes from the working directory to the staging area.

##How To's

###Personalize Git

Before you start playing with repos you want to let git know who you are. You only have to do this once:

```
git config --global user.name "Your Name"
git config --global user.email "your_email@whatever.com"
```

###Create a Project

```
# Create a new folder and go to it
mkdir hello
cd hello

# Initialize Git Project
git init
git add world.jpg
git commit -m 'Initial Commit'
```

##Learn More

* [Git Tower](http://www.git-tower.com/learn/videos)
* [Git Cheat Sheet](http://ndpsoftware.com/git-cheatsheet.html#loc=workspace;)
* [Git Documentation](http://git-scm.com/doc)
* [Git - The Simple Guide](http://rogerdudler.github.io/git-guide/)
* [Git Immersion](http://gitimmersion.com/)