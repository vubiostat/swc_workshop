# VUMC Software Carpentry Workshop

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