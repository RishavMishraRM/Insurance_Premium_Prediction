# Insurance Premium Prediction

## Overview

Insurance premium prediction with data

Reasearch Notebook files :

1. EDA Insurance dataset
2. Feature Engineering

Using black to organise code

## Key Features

- **Data Exploration:** Gain insights into the dataset through exploratory data analysis (EDA) to understand the distribution of features, correlations, and potential trends.

- **Predictive Modeling:** Utilize machine learning algorithms to build a predictive model capable of estimating restaurant ratings based on input features.

- **Interface:** Interact with the model through an intuitive user interface that allows users to input restaurant features and receive a predicted rating.

## Architecture

- **Python:**

### Folder Structure

```console
$ tree
.
│
├ .github
│    └── Workflow
│          ├── .gitkeep
│	       └──  YML Files
│
├── artifacts
│   ├── preprocessor.pkl
│   ├── model.pkl
│   ├── raw.csv
│   ├── test.csv
│   └── train.csv
│
├── Insurance_Premium_Prediction.egg-info(log_files)
│   └── log files
│
├── Notebook
│   ├── Data
│   │    └── insurance.csv(original data)
│   ├──catboost_info
│   │    │── catboost_training.json
│   │    │── learn_error.tsv
│   │    │── time_left.tsv
│   │    └── learn
│   │           └──events.out.tfevents
│   ├── research.ipynb
│   ├── Model_Training.ipynb
│   └── EDA.ipynb
│
├── SRC
│    └── Insurance_Premium_Prediction
│              ├── Components
│              │     ├── __init__.py
│              │     ├── data_transformation.py
│              │     ├── data_ingestion.py
│              │     └── model_trainer.py
│              │
│              ├── Pipelines
│              │     ├── __init__.py
│              │     ├── prediction_pipeline.py
│              │     └── training_pipeline.py
│              │
│              │── Utils
│              │     ├── __init__.py
│              │     └── utils.py
│              │
│              ├── __init__.py
│              ├── exception.py
│              └── logger.py
│
│
├── templates
│   ├── form.html
│   ├── index.html
│   └── result.html
│
├── README.md
│
├── Dockerfile
│
├── .gitignore
│
├── app.py
│
├── requirements.txt
│
├── MIT License
│
├── setup.py
│
├── template.py
│
├── test.py
│
└── init_setup.sh
```
