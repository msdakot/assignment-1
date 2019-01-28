# Installing Python

The Anaconda distribution of Python is a _package manager_ for Python. It is very widely used and there are a number of resources available online for Mac OS X and Windows machines.

The Anaconda distribution is free to install and can be downloaded using:

https://www.anaconda.com/download/

The latest installer for your computer's operating system should be used. It will install Python version 3.7 as well as many other Python-based packages.

Based on your operating system, installation instructions are available online:

- [Mac OS X](https://www.datacamp.com/community/tutorials/installing-anaconda-mac-os-x)
- [Windows](https://www.datacamp.com/community/tutorials/installing-anaconda-windows)

Note that if using Windows, it is recommended to select the option to add Anaconda to your PATH.

## Python 2 vs 3

The adoption of Python 3, first released in 2008, was very slow, and many users still choose to use Python 2. In my opinion, this is the wrong choice. Python 3 has a lot of great, new features, and starting in 2019, many of the main Python packages will no longer support Python 2.

## The Command Line

For windows users, the command-line emulator [cmder](http://cmder.net/) is recommended.
For Mac users, the built-in Terminal can be used or a replacement
application like [iTerm](https://www.iterm2.com/).

## Setting up a MUSA 620 Python environment

A new conda environment should be created and activated
using the [environment.yml](environment.yml) file in this repository.
From the command-line, run:

```
# create the environment
conda env create -f environment.yml

# make the environment active
source activate musa
```

For further information on the `conda` command, see
the [conda user guide](https://conda.io/projects/conda/en/latest/user-guide/).
