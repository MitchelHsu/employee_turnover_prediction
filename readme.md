# Employee Turnover Prediction and Analysis

## Contents
* How to Start (environment setup)
* Data description

## How to Start (environment setup)
To create and activate a conda environment (Python 3.7.13):
```
conda create -n emp python==3.7.13
```

To check if your environment is successfully created:
```
conda env list
```

Activate conda environment:
```
conda activate emp
```

To install the project's dependencies:
```
pip install -r requirements.txt
```

## Data description
* train.csv: yearly data (14,392 records in total)
* season.csv: quarterly data (72,684 records in total)
* test.csv: data of 2018 (3,739 records in total)
* submission.csv: Sample of upload file format，the columns include: 
* PerNo: personnel number
* PerStatus:  target of prediction，0 : retained；1: resigned