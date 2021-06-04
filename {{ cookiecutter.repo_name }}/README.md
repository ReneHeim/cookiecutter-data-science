{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

    ├── LICENSE
    ├── Makefile            <- Makefile with commands like `make data` or `make train`
    ├── README.md           <- The top-level README for developers using this project.
    ├── code
    │   ├── func.py         <- Python script containing all custom-built functions/modules. 
    │   ├── main.py         <- Python script containing the main data analysis.
    │   ├── eda.ipynb       <- Jupyter notebook containing exploratory data analysis.
    │   ├── cleaning.ipynb  <- Jupyter notebook containing data cleaning code. 
    │
    ├── data
    │   ├── clean           <- Data cleaned for analysis. Pay attention to naming scheme.
    │   ├── external        <- Data from third party sources.
    │   ├── raw             <- The original, immutable data dump. Never edit this data or use location to store other data.
    │   └── temp            <- Temporary data products. This data can always be deleted as it is supposed to be built from code.
    │
    ├── documents            
    │   ├── manuscript      <- Contains the manscript for publication.
    │   ├── reports         <- Contains data reports and presentations usually as jupyter notebooks.
    │
    ├── gis                 <- Contains image-processing and other GIS project files (e.g. QGIS and Agisoft projects)
    │
    ├── output
    │   ├── dfs             <- Produced data frames that are NOT CLEANED DATA.
    │   ├── tables          <- Data tables.
    │   ├── visualizations  <- .jpg, .gif, .png, and related file formats
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
