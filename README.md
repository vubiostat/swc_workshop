# VUMC Software Carpentry Workshop

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/vubiostat/swc_workshop)

This repository contains teaching materials for the VUMC Software Carpentry Workshop, held each summer by the Department of Biostatistics and the Department of Biomedical Informatics.

To obtain and use the materials for the workshop, you will need to have both Git and Python (version 3.5) installed on your system. Instructions for this are provided on the [workshop website](https://vubiostat.github.io/2016-08-17-vumc/). 

Having done this, follow the steps below for getting up and running with the course materials.

## Getting this repository

    git clone https://github.com/vubiostat/swc_workshop.git

If you are not familiar with Git and GitHub, you can simply download the zip file of the repository at the top of the main repository page.

Then, move to the directory created by the clone/zip file:

    cd swc_workshop

and install everything using `conda`:

    conda config --add channels conda-forge
    conda env create -f environment.yml
    
This will create an **environment** called `workshop` that includes the packages required for the course.    

To use the environment, you may type:

    source activate workshop
    
on MacOS and Linux, or:

    activate workshop
    
on Windows.

### Enabling parallel IPython

To enable IPython parallel computing in the notebook environment, type:

    ipcluster nbextension enable 
    
from the command line.
    
## Running Jupyter notebooks

To use any of the Jupyter notebooks included in this repository, run the following command from the terminal:

    jupyter notebook
    
This will open your default browser to Jupyter running on your system.

![Jupyter](http://d.pr/i/1hEz9/1h1qF9VH+)

Click on the `notebooks` directory, then on one of the enclosed notebook files (`.ipynb` extension) within.