Text Editor
===========
A text editor is a simple notepad type application. For the DRI, we will be using the sublime text editor because it supports [syntax highlighting](https://en.wikipedia.org/wiki/Syntax_highlighting) and works on every operating system. 

**Download sublime:** [sublime](https://www.sublimetext.com/)

Optional: Enable opening sublime from the command line:

[Windows](https://scotch.io/tutorials/open-sublime-text-from-the-command-line-using-subl-exe-windows)

**OSX:**

1) open a [terminal](anaconda.md#md)

2) type the following:

```bash
echo $PATH$
```
Take any of the listed paths, for example "/usr/local/bin" and then type:
```bash
ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin
```

If you get a `permission denied` error, type:

```bash
sudo ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin
```

Command Line
============
**Windows**: install [git-bash](https://git-for-windows.github.io/) for linux operating system commands

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

Git installs as a commandline tool. To check that it has been installed properly, open a [terminal](https://github.com/GCDigitalFellows/installdri.github.io/blob/master/anaconda.md) and type `git`. The terminal should then print the following:

![screenshot of git help screen dump](figs/gitinstall.png)

Note: While this is an OSX terminal, the same message should print in a Windows git-bash terminal. It may not print in an anaconda command prompt nor a Window's command prompt terminal because it requires further work for those terminals to recognize this installtion of git. 

Python
======
Download the Anaconda distribution of Python. This provides Python and the Jupyter notebook environment. 

**Download Python 3.6:** [Anaconda Python Distribution](https://www.continuum.io/downloads)

Check the following boxes on the installation menu:
 * Add to path
 * Register as default Python

## References ##

* [Anaconda Cheet Sheet](http://conda.pydata.org/docs/using/cheatsheet.html)

* [Jupyter Reference Sheet](https://damontallen.github.io/IPython-quick-ref-sheets/)

Databases
==========

**Download:** [SQLiteStudio](http://sqlitestudio.pl/)

This doesn't install onto your compter. To run it, enter the folder that you downloaded and _click_ on the file called `SQLiteStudio`. 

Optional: If you'd like to put the program in a permenant place:

* **OS/X:** Drag the SQLiteStudio icon to the applications folder

* **Windows:** 

  1) Move `SQLiteStudio` folder to somewhere (`Documents`, `Program Files`, etc...)

  2) Enter the folder and right click on `SQLiteStudio` 
  
  3) Click `pin to start` from the context menu (menu that pops up when you click on things) 

1. Open the [anaconda terminal](anaconda.md) to install [sqlite](https://docs.python.org/2/library/sqlite3.html). 
2. In the terminal, type the following: 

`conda install sqlite -y`

A successful install should look similar to the following:

![conda screenshot](figs/conda_install.png)


Note: sqlite3 may be installed in Python by default.

Troubleshooting
===============
[How can I tell if Windows is 32 bit or 64 bit?](http://windows.microsoft.com/en-us/windows/32-bit-and-64-bit-windows#1TC=windows-7)

[Change Security & Privacy settings on OS/X](https://support.apple.com/en-us/HT202491) to allow app downloads from outside sources. 

