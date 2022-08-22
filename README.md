# PetroFit Environments

This repository stores "frozen" conda environment files to serve as references for future installation. The environment files themselves are not provided as installation tools, as they contain more than what is required to run PetroFit, but are intended to serve as guides for compatible versions of packages at the time of each release. 


## Guide to Installing

**Note: Users should use environment files included in their copy of PetroFit for regular installation!** 

As stated above, these files are not intended for installation. 
If users decide to install an environment, the following commands can come in handy:  

```
 Run the following command to set up this environment:
 $ conda env create -f environment.yml

 The environment name can be overridden with the following command:
 $ conda env create -n <custom name> -f environment.yml

 Run the following command to activate the environment:
 $ source activate v_{x}_{y}_{z}_petrofit

 To deactivate the environment run the following command:
 $ source deactivate

 To remove the environment entirely, run the following command:
 $ conda env remove -n v_{x}_{y}_{z}_petrofit

```
