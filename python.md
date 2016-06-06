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
Copy the data to any of the folders listed  by the nltk.data.path command. If the command doesn't return anything, call for a helper.

