# My Data Science Projects Template ⛩️
My Data Science Projects Template using Cookiecutter

This whas just a first test to see how it works. I will try to make a more complex template in the future.

``` bash
pipx install cookiecutter
```

``` bash
cookiecutter https://github.com/PozzOver13/my_ds_template
```

Repository:
```
├── README.md
├── data
|   ├── raw                          <- The original, immutable data dump.
│   ├── processed                    <- The final, canonical data sets for modeling.
│
├── development                      <- Jupyter notebooks and Python Scripts. Naming convention to be defined
│
├── reports                          <- Generated analysis as XLSX, HTML, PDF, LaTeX, etc.
│
└── {{ cookiecutter.module_name }}   <- Source code for use in this project.
    ├── __init__.py                  <- Makes {{ cookiecutter.module_name }} a Python module
    │
    ├── config.py                    <- Store useful variables and configuration
```