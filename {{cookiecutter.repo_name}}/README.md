# {{ cookiecutter.repo_name }}

{{ cookiecutter.projecto_short_description }}

## Author
{{ cookiecutter.full_name }}

## Project Organization

...
├── .gitignore                <- GitHub's excellent Python .gitignore customized for this project
├── LICENSE                   <- Your project's license
├── HISTORY.md                <- The HISTORY changes track
├── README.md                 <- The top-level README for developers using this project.
│
├── data
│   ├── external              <- Data from third party sources.
│   ├── interim               <- Intermediate data that has been transformed.
│   ├── processed             <- The final, cannonical data sets for modeling.
│   └── raw                   <- The original, immutable data dump.
│
|
├── models                    <- Trained and serialized models, model predictions, or model summaries
|
├── notebooks                 <- Jupyter notebooks. Naming convention is a number (for ordering),
│                                the creator's initials, and a short `_` delimited description, e.g.
│                                `01_cp_exploratory_data_analysis.ipynb`.
│
|
├── references                <- Data dictionaries, manuals, and all other explanatory materials.
|
├── reports                   <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures               <- Generated graphics and figures to be used in reporting.
|
├── requirements.txt          <- The requirements file for reproducing the analysis environment, e.g.
|                                generated with 'pip freeze < requirements.txt'
|
├── {{ cookiecutter.module_name }}
    |
    ├── __init.py__           <- Makes {{ cookiecutter.module_name }} a Python module
    |
    ├── config.py             <- Store useful variables and configuration
    |
    ├── dataset.py            <- Scripts to download or generate data
    |
    ├── features.py           <- Code to create features for modeling
    |
    ├── modeling
    |   ├── __init.py__
    |   ├── predict.py        <- Code to run model inference with trained models
    |   └── train.py          <- Code to train models
    |
    └── plots.py              <- Code to create visualizations
...

## Requirements
Python {{ cookiecutter.version_python }}

## Licencia
{{ cookiecutter.open_source_license }}
        