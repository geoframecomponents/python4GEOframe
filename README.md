# python4GEOframe
Python stuff for GEOframe 

## Conda environment
A [conda environment](https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/environments.html) is a directory that contains a specific collection of conda packages that you have installed. For example, you may have one environment with NumPy 1.7 and its dependencies, and another environment with NumPy 1.6 for legacy testing. If you change one environment, your other environments are not affected. You can easily activate or deactivate environments, which is how you switch between them. You can also share your environment with someone by giving them a copy of your environment.yaml file. For more information, see Managing environments.

Anaconda\_envs contains all the version of the .yaml file we released. In order 
- geoframe\_vicenza.yaml 
- geoframe_rossano.yaml

To create a new conda environment:
- open the Anaconda prompt
- set in the .yaml folder
- `conda env create -f geoframe_xxx.yaml`
- `conda activate geoframe_xxx`

Once the geoframe environment is created, a JDK 8 is installed on your computer. To know the JAVA_HOME 
- open the Anaconda prompt
- `conda activate geoframe_xxx`
- `echo JAVA_HOME`

## gridGEO1D
This folder contains the notebooks and the python scripts to create a one-dimensional grid for finite volumes.
