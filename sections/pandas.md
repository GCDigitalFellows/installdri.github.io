# Pandas

Pandas is the [Python Data Analysis](https://pandas.pydata.org/) library and provides high level statistical analysis. It is installed via the [conda](conda.md) package managment system.

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
    libcxxabi:       4.0.1-hebd6815_0                   
    libedit:         3.1.20170329-hb402a30_2            
    libffi:          3.2.1-3                 conda-forge
    libgfortran:     3.0.1-h93005f0_2                   
    libopenblas:     0.2.20-hdc02c5d_7                  
    ncurses:         6.1-0                   conda-forge
    numpy:           1.14.3-py36he6379a5_2              
    numpy-base:      1.14.3-py36h7ef55bc_1              
    openssl:         1.0.2o-0                conda-forge
    pandas:          0.23.0-py36_1           conda-forge
    pip:             10.0.1-py36_0                      
    python:          3.6.5-hc167b69_1                   
    python-dateutil: 2.7.3-py_0              conda-forge
    pytz:            2018.4-py_0             conda-forge
    readline:        7.0-hc1231fa_4                     
    setuptools:      39.2.0-py36_0           conda-forge
    six:             1.11.0-py36_1           conda-forge
    sqlite:          3.23.1-hf1716c9_0                  
    tk:              8.6.7-0                 conda-forge
    wheel:           0.31.1-py36_0                      
    xz:              5.2.4-h1de35cc_4                   
    zlib:            1.2.11-h470a237_3       conda-forge

ncurses-6.1-0. 100% |########################################| Time: 0:00:00   2.30 MB/s
xz-5.2.4-h1de3 100% |########################################| Time: 0:00:00   3.04 MB/s
zlib-1.2.11-h4 100% |########################################| Time: 0:00:00   6.48 MB/s
libedit-3.1.20 100% |########################################| Time: 0:00:00   9.94 MB/s
libopenblas-0. 100% |########################################| Time: 0:00:01   8.78 MB/s
sqlite-3.23.1- 100% |########################################| Time: 0:00:00  10.08 MB/s
python-3.6.5-h 100% |########################################| Time: 0:00:01   9.62 MB/s
numpy-base-1.1 100% |########################################| Time: 0:00:00   6.10 MB/s
numpy-1.14.3-p 100% |########################################| Time: 0:00:00  21.70 MB/s
python-dateuti 100% |########################################| Time: 0:00:00   5.81 MB/s
setuptools-39. 100% |########################################| Time: 0:00:00   1.92 MB/s
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
