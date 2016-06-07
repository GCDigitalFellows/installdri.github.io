Python Libraries:
=================
Install the packages for the Python course via the `conda` Python package system. Links to the libraries are provided **only** for reference.

1) open the [anaconda terminal](anaconda.md)

2) type the commands listed for each session: 

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
Install everything from [Time Series & Catagorical Data Analysis](#time-series--catagorical-data-analysis)
and [sklearn](http://scikit-learn.org/stable/):
```
conda install scikit-learn -y
```

NLTK
----

Install the [NLTK](http://www.nltk.org/) library:

```
conda install nltk -y
```
While still in the conda shell, type `python`

once in the python interpreter, you should see `>>>`. Then type (1st line then press enter, 2nd line then press enter):

```python
import nltk
nltk.download('all', halt_on_error=False)
```

###Troubleshooting
If the downloader does not work, download the corpus by [clicking here](https://github.com/nltk/nltk_data/archive/gh-pages.zip) or use a local copy. Then 
1) Open an [anaconda terminal](anaconda.md)
2) type:
```python
import nltk
nltk.data.path
```
1) Copy the data to any of the folders listed  by the nltk.data.path command.

2) Put the `corpora` folder in the top level of `nltk_data`

If you want to use a custom folder:

1) copy the contents of the folder on the usb to '...\\Anaconda\\lib'. The `lib` folder should now containd a folder named `nltk_data`

2) find the path of the nltk_data folder:
  * [Find path on windows](http://www.dummies.com/how-to/content/how-to-find-a-folders-path-name-in-windows-explore.html)

  * [Find path on OSX](http://osxdaily.com/2015/11/05/copy-file-path-name-text-mac-os-x-finder/)

3) save that path using your text editor of choice

4) open the [anaconda prompt](anaconda.md) and type `python`
  
5) once in the python interpreter, you should see `>>>`. Then type:

```python
import nltk
nltk.data.path = nltk.data.path.append(path_you_copied)
```

Check if it installed properly by opening a python terminal and typing

```python
import nltk.book
```

# Check other installs
Check if a library is installed by trying to import it into python. First type `python` and then once in the interpreter, you should see `>>>`. Then type:

```python
import flask
import scipy
import pandas
import matplotlib
import sklearn
import nltk
```
