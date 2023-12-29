# Insurance Premium Prediction

Insurance premium prediction with data

Completed EDA, Feature Engineering & code testing

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

