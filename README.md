# Sentiment Analysis

## Topic Modeling Project

## Project Structure
├── README.md          <- The top-level README for developers using this project.

├── data

│   ├── external       <- Data from third party sources.

│   ├── interim        <- Intermediate data that has been transformed.

│   └── raw            <- The original, immutable data dump.

│

├── models             <- Trained and serialized models, model predictions, or model summaries

│

├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),

│                         the creator's initials, and a short `-` delimited description, e.g.

│                         `1.0-jqp-initial-data-exploration`.

│

├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.

│                         generated with `pip freeze > requirements.txt`

│

├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported

├── src                <- Source code for use in this project.

│   ├── __init__.py    <- Makes src a Python module

│   │

│   ├── data           <- Scripts to download or generate data

│   │   └── prepare_data.py

│   │   └── split.py

│   │

│   ├── features       <- Scripts to turn raw data into features for modeling

│   │   └── dictionary.py

│   │   └── tokenize.py

│   │   └── utils.py

│   │

│   ├── models         <- Scripts to train models and then use trained models to make

│   │   │                 predictions

│   │   ├── predict.py

│   │   └── train.py

│   │

│   └── visualization  <- Scripts to create exploratory and results oriented visualizations

│       └── visualize.py

│

└── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io

