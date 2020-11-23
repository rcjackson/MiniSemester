# MiniSemester

This is the GitHub repository for the Argonne Mini-Semester Course on Introductory Python. 

Installation
------------

First, in order to run the tutorials, you will need to install the Anaconda distribution. Anaconda is a package manager that will automatically determine what libraries you need to download in order to run your favorite packages. It comes packaged with Python along with standard scientific Python libraries such as NumPy, SciPy, Matplotlib and Pandas. In order to download Anaconda for your computer, click on the following link to download the installation executable for your computer:

https://www.anaconda.com/products/individual

After that, you'll need to initialize the development environment for the tutorial. In order to do this, go into a terminal or the Anaconda Prompt, and, first, install git:
```
   conda install -c conda-forge git
```   
After installing git, clone this repository:
```
   git clone https://github.com/rcjackson/MiniSemester
```   
Finally, change into the directory and initialize the environment:
```
   cd MiniSemester
   conda env create -f environment.yml
```

To activate an environment in anaconda, simply type in the prompt:
```
   conda activate tutorial_env
```   
To leave an environment, simply type:
```
   conda deactivate
```
