# SolarPhysicsExamples
Set of Python examples for Solar Physics Module (UCL)

# Binder Repository to a notebook
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/D-DePablos/SolarPhysicsExamples/master)

# Local Installation (Useful if Internet Connection unstable)
1. Install Anaconda, a Python and Data Science package manager 
https://www.anaconda.com/products/individual

2. Use the environment.yml file to install relevant packages:
  - Generate relevant environment: conda env create solarphysics
  - Install environment.yml file: conda env update -n solarphysics --file environment.yml
  
3. Open the Notebook in Jupyter, either from the Anaconda GUI (Windows, MAC), or from the Anaconda Prompt:
jupyter notebook Notebookfile.ipynb
