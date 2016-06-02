Text Editor
===========
A text editor is a simple notepad type application. For the DRI, we will be using the sublime text editor because it supports [syntax highlighting](https://en.wikipedia.org/wiki/Syntax_highlighting) and works on every operating system. 

**Download sublime:** [sublime](https://www.sublimetext.com/)

**Make it so commandline can see the program:** [OSX](http://www.sublimetext.com/docs/3/osx_command_line.html), [Windows](https://scotch.io/tutorials/open-sublime-text-from-the-command-line-using-subl-exe-windows) 

Command Line
============
**Windows**: [windows terminal is git-bash](https://git-for-windows.github.io/)

**OSX:**

1) open a [terminal](https://github.com/GCDigitalFellows/installdri.github.io/blob/master/anaconda.md#mac)

2) type the following in the terminal:
```
xcode-select --install
```


Git
============
**OSX/Linux Install:** [git](https://git-scm.com/)

**Windows Install:** [git-windows-tools](https://git-for-windows.github.io/)

**Register:** [Github](https://github.com/)

Python
======
Download the Anaconda distribution of Python. This provides Python and the Jupyter notebook environment. 

**Download Python 3.5:** [Anaconda Python Distribution](https://www.continuum.io/downloads)

Check the following boxes on the installation menu:
 * Add to path
 * Register as default Python

##References##
[Anaconda Cheet Sheet](http://conda.pydata.org/docs/using/cheatsheet.html)

[Jupyter Reference Sheet](https://damontallen.github.io/IPython-quick-ref-sheets/)

Databases
==========

**Download:** [SQLiteStudio](http://sqlitestudio.pl/)

This doesn't install onto your compter. To run it, enter the folder that you downloaded and _click_ on the file called `SQLiteStudio`. 

Open the [anaconda terminal](anaconda.md) to install [sqlite](https://docs.python.org/2/library/sqlite3.html) by typing the following: 

`conda install sqlite -y`

A successful install should look similar to the following:

![conda screenshot](https://github.com/GCDigitalFellows/installdri.github.io/blob/master/conda_install.png)


Note: sqlite3 may be installed in Python by default.

Troubleshooting
===============
[How can I tell if Windows is 32 bit or 64 bit?](http://windows.microsoft.com/en-us/windows/32-bit-and-64-bit-windows#1TC=windows-7)

[Change Security & Privacy settings on OS/X](https://support.apple.com/en-us/HT202491) to allow app downloads from outside sources. 

