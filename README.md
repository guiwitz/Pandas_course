[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/guiwitz/Pandas_course/master)

# Science IT Support Pandas course 

This is the support material for a course on the Python package Pandas given at Bern University by Guillaume Witz from the Science IT Support team. The material consists of a series of interactive Jupyter notebooks using open data from diverse sources.

If you want to set-up an environment to use the material outside of the JupyterHub provided during the lecture, please follow theses steps:
- Copy this repository on your computer
- Install the [conda environment manager](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)
- Create a new environment dedicated to the course, e.g in a terminal type:
```
conda create -n pandas_course numpy matplotlib pandas jupyter jupyterlab pip seaborn scikit-learn
source activate pandas_course
pip install plotnine
```
and close the terminal
- Whenever you want to use the environment activate it:
```
source activate pandas_course
```
- Start Jupyter:
```
jupyter notebook
```
- Navigate to the course folder

You will need to download some data and put it in the folder called ```Datasets``` at the same level as the Pandas_course repository folder.
- Execute the notebooks called [Pandas_downloads.ipynb](Notebooks/Pandas_downloads.ipynb) to do that
