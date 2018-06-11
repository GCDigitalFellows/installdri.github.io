# Conda Package Management
Programming libraries get their name from the physical equivalent – just like the GC library provides books that can help a project along, programming libraries provide code encapsulated as functions and objects to carry out tasks common to the domain of the library. Libraries need to be installed into programming environments to be used - in our case that's probably an [Anaconda](python.md) environment. To do so, we use the `conda` package management system. 

## How to install a Python library 

1. *Open* a [windows](windows_terminal.md) or [OS/X](osx_terminal.md) terminal
2. *Type* the following into the terminal, replacing [name of library] with the name of the library you would like to install.
```shell
conda install [name of library] -y
```

Example:

To install the `numpy` library, I type:
```shell
conda install numpy -y
```

The terminal then prints something like:
```shell
Fetching package metadata .......
```

It may take awhile, but eventually the terminal will resolve and print the results of the command. You may see something like this (the exact wording will vary based on what is already installed):

```shell
Fetching package metadata .............
Solving package specifications: .

Package plan for installation in environment /Users/hannah/miniconda3/envs/scraping:

The following NEW packages will be INSTALLED:

    blas:         1.1-openblas          conda-forge
    openblas:     0.2.20-8              conda-forge

The following packages will be UPDATED:

    numpy:        1.14.0-py36h8a80b8c_1             --> 1.14.3-py36_blas_openblas_200 conda-forge [blas_openblas]
    scikit-learn: 0.19.1-py36hffbff8c_0             --> 0.19.1-py36_blas_openblas_201 conda-forge [blas_openblas]
    scipy:        1.0.0-py36h1de22e9_0              --> 1.1.0-py36_blas_openblas_200  conda-forge [blas_openblas]

openblas-0.2.2 100% |################################| Time: 0:00:02   8.32 MB/s
scipy-1.1.0-py 100% |################################| Time: 0:00:01  10.67 MB/s
```

If the library is already installed, the terminal will print something like:
```shell
Fetching package metadata .............
Solving package specifications: .

# All requested packages already installed.
# packages in environment at /Users/hannah/miniconda3/envs/scraping:
#
numpy                     1.14.3          py36_blas_openblas_200  [blas_openblas]  conda-forge
```
Test your install by opening a python interpreter (REPL) by typing `python` into the terminal. You should see something like:

```python
Python 3.6.4 | packaged by conda-forge | (default, Dec 23 2017, 16:54:01) 
[GCC 4.2.1 Compatible Apple LLVM 6.1.0 (clang-602.0.53)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

Then try to load the library we just installed:
```python
>>> import numpy
>>> 
```

If the library is not installed, there will be an error:
```python
Python 3.6.4 | packaged by conda-forge | (default, Dec 23 2017, 16:54:01) 
[GCC 4.2.1 Compatible Apple LLVM 6.1.0 (clang-602.0.53)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import numpy
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ModuleNotFoundError: No module named 'numpy'
>>> 
```