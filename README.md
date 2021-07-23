## What is this?
The goal of this repository is to make a fairly simple file structure that will allow the user to streamline project creation and create standards across groups. Noteably, this is an **extremely** minimal version of what can be done both with cookiecutter and the cookiecutter-data-science fork. 


## Install

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------

    cookiecutter https://github.com/anpatton/cookiecutter-data-science
    
    
### After you follow the prompts create a conda environment with the same name as the repo name from the propmts
------------

    conda create --name repo_name_goes_here
    
### Once our environment is active and has the packages you need (this can be done multiple times as you add/remove dependencies)
------------

    conda env export --name env_name_goes_here > env_name_goes_here.yml

The directory structure of your new project looks like this: 

### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── results            <- Generated analysis, final results, predictions, etc.
│   └── figures        <- Generated graphics and figures 
│
├── env_name_goes_here.yml <- The requirements file for reproducing the analysis environment (user created after the fact)
│
├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
```
