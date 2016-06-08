Python Libraries:
=================
Install the libraries for the Python course via the `conda` Python package system. Links to the libraries are provided **only** for reference.

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

This command will likely fail or hang when trying to download panlex_lite. If that happens, please kill the download (closing the terminal will work) and move on to the troubleshooting steps. 

###Troubleshooting
If the downloader does not work:

1) download the corpus by [clicking here](https://github.com/nltk/nltk_data/archive/gh-pages.zip) or get it from the usb

2) extract the folder and rename it `nltk_data`

3) Move the `nltk_data` folder inside the following folder on your computer: (Replace `hannah` with the username on your computer)
  * **Windows:** `C:\\Users\\hannah`
  * **OS/x, Linux:** `/Users/hannah/`

4) Move everything in the `packages` folder of `nltk_data` to the top level of the `nltk_data` folder. This means that the contents of your  `nltk_data` folder should be as follows:
```bash
test:nltk_data hannah$ ls
Makefile	     corpora	     index.xsl	    stemmers
README.txt	   grammars	    misc		        taggers
chunkers	     help		       models		      tokenizers
collections	  index.xml	   sentiment	    tools
```

Check if it is installed properly by opening a python terminal and typing

```python
import nltk.book
```

Check other installs
====================
Check if a library is installed by trying to import it into python. First type `python` and then once in the interpreter, you should see `>>>`. Then type:

```python
import flask
import scipy
import pandas
import matplotlib
import sklearn
import nltk
```
