# Pandas

[Pandas](https://pandas.pydata.org/) is the Python Data Analysis library. It is installed via the [conda](conda.md) package managment system and may already be installed in your environment.

## Install Pandas

1. *Open* a [windows](windows_terminal.md) or [OS/X](osx_terminal.md) terminal
2. *Type* the following into the terminal:

```shell
conda install pandas -y
```

The terminal should print something like the following:

```bash
Fetching package metadata .............
Solving package specifications: .

Package plan for installation in environment /Users/hannah/miniconda3/envs/installenv:

The following NEW packages will be INSTALLED:

    ca-certificates: 2018.4.16-0             conda-forge
    certifi:         2018.4.16-py36_0        conda-forge
    libcxx:          4.0.1-h579ed51_0      

        .... omitted text ....

pandas-0.23.0- 100% |########################################| Time: 0:00:03   4.12 MB/s
wheel-0.31.1-p 100% |########################################| Time: 0:00:00   2.89 MB/s
pip-10.0.1-py3 100% |########################################| Time: 0:00:00  14.36 MB/s
```
## Test Pandas install
While still in the terminal, launch the Python interpreter by *typing* `Python`. You should then see something like:
```python
Python 3.6.5 |Anaconda, Inc.| (default, Apr 26 2018, 08:42:37) 
[GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

Then try to load Pandas by typing `import pandas` If everything has installed correctly, you will then see a blank line starting with `>>>` underneath, as shown below. 
```python
Python 3.6.5 |Anaconda, Inc.| (default, Apr 26 2018, 08:42:37) 
[GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import pandas
>>> 
```

If the installation failed, the terminal will print an error. 
