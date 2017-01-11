Python Libraries:
=================
Install the libraries for the Python course via the `conda` Python package system. Links to the libraries are provided **only** for reference.

1) open the [anaconda terminal](anaconda.md)

2) type the commands listed for each session: 

Twitter API
--------------------------
Install [Tweepy](https://github.com/tweepy/tweepy):
```
pip install tweepy
```

Quantative Analysis & Textual Analysis
----------------------------------------
Should be installed in conda by default. Otherwise install [pandas](http://pandas.pydata.org/), and [sklearn](http://scikit-learn.org/stable/):
```
conda install pandas -y
conda install scikit-learn -y
```


Check other installs
====================
Check if a library is installed by trying to import it into python. First type `python` and then once in the interpreter, you should see `>>>`. Then type:

```python
import tweepy
import pandas
import sklearn
```
