# Scikit-Learn

[Scikit-Learn](http://scikit-learn.org/stable/index.html) is a library for doing machine learning in Python. It is installed via the [conda](conda.md) package managment system and may already be installed in your environment.

## Install Scikit-Learn

1. *Open* a [windows](windows_terminal.md) or [OS/X](osx_terminal.md) terminal
2. *Type* the following into the terminal:

```shell
conda install scikit-learn -y
```
The terminal should print something like the following:

```bash
Fetching package metadata .............
Solving package specifications: .

Package plan for installation in environment /Users/hannah/miniconda3/envs/installenv:

The following NEW packages will be INSTALLED:

    blas:         1.1-openblas                  conda-forge
    openblas:     0.2.20-8                      conda-forge
    scikit-learn: 0.19.1-py36_blas_openblas_201 conda-forge [blas_openblas]
    scipy:        1.1.0-py36_blas_openblas_200  conda-forge [blas_openblas]

The following packages will be UPDATED:

    numpy:        1.14.3-py36he6379a5_2                     --> 1.14.3-py36_blas_openblas_200 conda-forge [blas_openblas]
```
## Test Scikit-Learn  install

While still in the terminal, launch the Python interpreter by *typing* `Python`. You should then see something like:
```python
Python 3.6.5 |Anaconda, Inc.| (default, Apr 26 2018, 08:42:37) 
[GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

Then try to load scikit-learn by typing `import sklearn` If everything has installed correctly, you will then see a blank line starting with `>>>` underneath, as shown below. 
```python
Python 3.6.5 |Anaconda, Inc.| (default, Apr 26 2018, 08:42:37) 
[GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import sklearn
>>> 
```

If the installation failed, the terminal will print an error. 
