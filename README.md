# Machine Learning Project Template

### Requirements to use this template:
-----------
 - Python >= 3.6
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------

    cookiecutter https://github.com/thanhtcptit/ml_template




### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── LICENSE
├── README.md                   <- The top-level README for developers using this project
│
├── configs                     <- Store experiment config files
│
├── data
│   ├── external                <- Data from third party sources
│   ├── interim                 <- Intermediate data that has been transformed
│   ├── processed               <- The final, canonical data sets for modeling
│   └── raw                     <- The original, immutable data dump
│   
├── train_logs                  <- Trained and serialized models, model predictions, or model summaries
│   
├── notebooks                   <- Jupyter notebooks. Naming convention is a number (for ordering),
│                                  the creator's initials, and a short `-` delimited description, e.g.
│                                  `1.0-jqp-initial-data-exploration`
│
├── references                  <- Data dictionaries, manuals, and all other explanatory materials
│   
├── reports                     <- Generated analysis as HTML, PDF, LaTeX, etc
│   └── figures                 <- Generated graphics and figures to be used in reporting
│   
├── requirements.txt            <- The requirements file for reproducing the analysis environment, e.g.
│                                  generated with `pip freeze > requirements.txt`
│   
├── setup.py                    <- Makes project pip installable (pip install -e .) so src can be imported
├── src                         <- Source code for use in this project.
│   ├── __init__.py             <- Makes src a Python module
│   ├── evaluate.py             <- Script to evaluate models
│   ├── export.py               <- Script to export model for serving
│   ├── hyperparams_search.py   <- Script to perform hyperparameter search
│   ├── train.py                <- Script to train models
│   │
│   ├── data                    <- Scripts to download or generate data
│   │   └── preprocess_dataset.py
│   │
│   ├── features                <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models                  <- Scripts to define models
│   │   └── base.py
│   │
│   ├── utils                   <- Scripts to define helper function
│   │
│   └── visualization           <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── tox.ini                     <- tox file with settings for running tox; see tox.readthedocs.io
```

### Installing development requirements
------------

    pip install -r requirements.txt
