# PyDataSciMeetup Setup
Just the requirements for a Data Science tutorial.

 ## Install Miniconda (or Anaconda)
 
 If haven't done so, download and install the lastest version of (https://conda.io/miniconda.html)[Miniconda] (A much smaller distribution of Anaconda) or full (https://www.continuum.io/downloads)[Anaconda].
 
 ## Clone this Repository
 
 Clone this repository.
 
```
cd ~/my_projects
git clone https://github.com/josian/PyDataSciMeetup.git
cd PyDataSciMeetup
```

## Create and Activate Conda Environment

This will create a Conda environment with the recommended packages and python version (Python 3.5).  It should take a few minutes to install all package dependencies.

```
conda create --name=DataSciMeetup --file=requirements.txt python=3.5
source activate DataSciMeetup
```

## Start Jupyter Notebook

To start the Jupyter notebook app, execute:

```
jupyter notebook
```

A browser should open up with the Jupyter app showing the main directory with the test notebook.  If you made it this far, you are ready for the Meetup.
