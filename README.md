# 2017_Kusmartseva_et_al_HospTime

This repository contains [Jupyter Notebooks](http://jupyter.org/), and their dependencies, allowing recreation of our results. 
The data was analyzed using [SAS](http://www.sas.com/en_us/home.html) and R.  Jupyter Notebooks support a growing number of [languages](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels), however running the SAS kernel requires a LINUX system which in turn requires a SAS licence for LINUX.


## Getting started

LINUX users with SAS licence can follow these [instructions](https://github.com/sassoftware/sas_kernel). Everybody else can install the free [SAS University Edition](www.sas.com/en_us/software/university-edition.html#), which is a virtual machine that can be run with [VirtualBox](https://www.virtualbox.org/), which is available for free as well. Both run on all operating systems.
Once SAS University Edition is added to VirtualBox a shared folder can be setup. This folder must be named SASUniversityEdition and it must contain a folder named "myfolders". This repository has the correct file structure already. So cloning this repository to any place in your file system and then pointing to myfolders will allow SAS to access the necessary files. 
After starting the SAS University Edition a browser can be pointed to http://localhost:18888.

## Using this repository

For those who don't want to install SAS University Edition but still want to have a look at the code and its output we provided html version of the notebooks. At the writing of this readme file, Github does not render html, hence we recommend you download the html files and to open them in a browser.


