## My gitignore File

I need a spot to stick my gitignore file. This is that spot.

There are two kinds of files here: global and project related.

### Global

The global gitignore is where I stash items that are useful for every or nearly every project.

This covers my OS and tool preferences.

#### Global gitignore File Name
.gitignore_global

#### Adding Global gitignore_global

git config --global core.excludesfile ~/.gitignore_global

Obviously, you need to specify the correct path if it isn't ~/.gitignore_global

#### My OS and Tool Sections

* Vim
* Windows
* Visual Studio
* Eclipse

### Project

These are specific to a type of project. For instance, node.js or Android.

### Links

Giving credit where credit is due:

[Github Article: "Ignoring-Files"](https://help.github.com/articles/ignoring-files)

[Github Project With Ignore File Samples](https://github.com/github/gitignore)

