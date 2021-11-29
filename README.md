Wardrobe-Recommender
==============================
TODOs

👉🏻 System Design: Model-as-a-Service (https://fullstackdeeplearning.com/spring2021/lecture-11/#model-as-service)

   ◻️ CI/CD
   
   ◻️ Testing
        
        ◻️ Code: PyTest
        
        ◻️ Data: Great Expectations
        
   ◻️ Experiment Tracking, etc
        
        ◻️ MLFlow: https://cloud.google.com/architecture/setting-up-mlops-with-composer-and-mlflow

   ◻️ Serving Solution: 
        
        ◻️ REST API (FastAPI)
        
        ◻️ Containerization: Docker

   ◻️ WebApp: Streamlit
    

 👉🏻 Some interesting architecture/system design/case studies (GCP): 
 
        🔗 https://cloud.google.com/architecture/real-time-item-matching?hl=en
        
        🔗 https://cloud.google.com/architecture/integrating-monitoring-logging-trace-observability-and-alerting?hl=en
        
        🔗https://cloud.google.com/architecture/best-practices-for-operating-containers?hl=en
        
        🔗https://cloud.google.com/architecture/minimizing-predictive-serving-latency-in-machine-learning?hl=en
        
        🔗https://cloud.google.com/architecture/jenkins-on-kubernetes-engine?hl=en
        
        🔗https://cloud.google.com/architecture/building-real-time-embeddings-similarity-matching-system?hl=en
        
        🔗https://cloud.google.com/architecture/setting-up-an-mlops-environment?hl=en
        
        🔗https://cloud.google.com/architecture/continuous-training-pipeline-with-composer-and-mlflow?hl=en
        
        🔗https://cloud.google.com/architecture/processing-streaming-time-series-data-overview?hl=en
        
        🔗https://cloud.google.com/architecture/real-world-insights-reference-architecture?hl=en
        
        🔗https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning
        
        🔗https://cloud.google.com/architecture/reference-patterns/overview



Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
