{{cookiecutter.project_name}}
==============================
Group: {{cookiecutter.plm_group}}  
Author: {{cookiecutter.author_name}}. 
Author Email: {{cookiecutter.author_email}}. 

Description
==============================
{{cookiecutter.description}}

Project Organization
------------
```
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries (pickles go here)
│
├── notebooks          <- Jupyter notebooks
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── results            <- Generated analysis, final results, predictions, etc.
│   └── figures        <- Generated graphics and figures 
│
├── env_name_goes_here.yml <- The requirements file for reproducing the analysis environment (UPDATE WHEN CREATED)
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
--------
