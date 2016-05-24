Python Libraries:
=================
Install the packages for the Python course via the `conda` Python package system. Links to the libraries are provided **only** for reference.

1) open the [anaconda terminal](anaconda.md)

2) find the class you plan to take in the list below

3) type the commands listed for each course. 

Web Framework Development
--------------------------
Install [flask](http://flask.pocoo.org/):
```
conda install flask -y
```

Time Series & Catagorical Data Analysis
----------------------------------------
Install [numpy](http://www.numpy.org/), [scipy](https://www.scipy.org/), 
[matplotlib](http://matplotlib.org/), & [pandas](http://pandas.pydata.org/):
```
conda install numpy -y
conda install scipy -y
conda install matplotlib -y
conda install pandas -y
```

Machine Learning
----------------
Install everything from 
[Time Series & Catagorical Data Analysis](#Time-Series-&-Catagorical-Data-Analysis)
and [sklearn](http://scikit-learn.org/stable/):
```
conda install sklearn -y
```

NLTK
----

Install the [NLTK](http://www.nltk.org/) library:

```
conda install nltk -y
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
  




