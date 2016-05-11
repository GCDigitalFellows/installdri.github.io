Download Python
==================
Download the Anaconda distribution of Python. This provides Python and the Jupyter notebook environment. 
[Anaconda Python Distribution](https://www.continuum.io/downloads)

[Anaconda Cheet Sheet](http://conda.pydata.org/docs/using/cheatsheet.html)
[Jupyter Reference Sheet](https://damontallen.github.io/IPython-quick-ref-sheets/)


Navigate to the anaconda shell
==============================
[screen shot tutorial/manual]

Python Libraries:
=================
1) open the anaconda shell

2) find the class you plan to take

3) type the commands listed for each course. 

Web Framework Development
--------------------------
```
conda install flask
```

Time Series & Catagorical Data Analysis
----------------------------------------

```
conda install numpy
conda install scipy
conda install matplotlib
conda install pandas
conda install basemap #maybe
```

Machine Learning
----------------
Install everything from *Time Series & Catagorical Data Analysis* and:
```
conda install sklearn
```

NLTK
----
```
conda install nltk
python -m nltk.downloader all
```
##Troubleshooting##
If the downloader does not work, install the corpus via a local copy (on the USB):
1) Copy the contents of the folder on the usb to '...\\Anaconda\\lib'. The `lib` folder should now containd a folder named `nltk_data`

2) Find the path of the nltk_data folder:
  * [Find path on windows](http://www.dummies.com/how-to/content/how-to-find-a-folders-path-name-in-windows-explore.html)

  * [Find path on OSX](http://osxdaily.com/2015/11/05/copy-file-path-name-text-mac-os-x-finder/)

3) Store that path to your text editor of choice

4) Open a python shell by: 

  i) (opening a command line)[cmd.md]

  ii) type `python`
5) Once you're in the python shell, type:

```
>>> import nltk
>>> nltk.data.path.append(path_you_copied)
```

  Replace path_you_copied with the path you found and stored in 2 & 3. For example, if I had copied 
  my data to `'C:\\Users\\hannah\\Anaconda\\lib\\nltk_data'`, then I would type:

```
>>> import nltk
>>> nltk.data.path.append('C:\\Users\\hannah\\Anaconda\\lib\\nltk_data')
```
  




