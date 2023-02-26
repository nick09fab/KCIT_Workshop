# KCIT_Workshop
Notebooks for KCIT ML Workshop


This repository has been created for KCIT Yugam Workshop and Recommendation system notebook.


## Environment setup
We recommend using a python virtual environment:
```
mkdir virtualenvs
virtualenv --python=python3 virtualenv

```
Fill in and set paths:
```
export BASEPATH=[path to the repo]
# RAW_DIR can be empty if using extracted feature files.
export RAW_DIR=[path to the raw data]

source ~/virtualenvs/col2type/bin/activate

```
Install required packages
```
cd $BASEPATH
pip install -r requirements.txt
```

```
.
├── data                   # Data Files (alternatively `dist`)
    ├── user_reviews.csv   # E-com Source dataset
├── model                  # Recommendation and NLP models
├── notebooks              # Python notebooks
├── sher_features          # Automated tests (alternatively `spec` or `tests`)
├── utils                   # Tools and utilities
├── requirements.txt
└── README.md

```