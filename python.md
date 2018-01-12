Python Libraries:
=================
Install the libraries for the Python course via the `conda` Python package system. Links to the libraries are provided **only** for reference.

To install a packaged via conda or pip: 

1) open a [terminal](anaconda.md)

2) type the listed commands

Twitter API
--------------------------
Install [Tweepy](https://github.com/tweepy/tweepy):
```
pip install tweepy
```

Quantative Analysis & Textual Analysis
----------------------------------------
These should be installed in conda by default. Otherwise install [pandas](http://pandas.pydata.org/), and [sklearn](http://scikit-learn.org/stable/):
```
conda install pandas -y
conda install scikit-learn -y
```

Textual Analysis
-----------------
Follow the [NLTK install instructions][nltk.md]

Check installs:
====================
Check if a library is installed by trying to import it into python. 

1. open a [terminal](anaconda.md)
2. type `python`. Once in the interpreter, you should see `>>>`. 
3. Check that the packages are installed by trying to import them. Type:

```python
import tweepy
import pandas
import sklearn
```
