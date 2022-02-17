# CFLDelays
![badge1](https://img.shields.io/badge/language-Python-01B0F0.svg)
![badge2](https://img.shields.io/badge/data-CFL-red.svg)
> Prediction of CFL multimodal trip delays.
## A Regression approach to perform a short-term predictive model
This model implements a lightGBM model to predict CFL multimodal trip delays using significative features.
In addition, it includes an streamlit app in order to run a web-service for the same regression approach.

## How to use  CFLDelays
### 1. Prerequisites
To be able to run this app, you need to have:
* [Python 3.8](https://www.python.org/downloads/)
* Run the code using the pipenv shell:
```
sudo apt install pipenv -y
pipenv shell
pipenv install --skip-lock
```

### 2. Run
Once the configuration is complete, it's time to run this app.
Simply run the following command lines below in a terminal:
```
pipenv run python ./scripts/preparing.py
pipenv run python ./scripts/etl.py
pipenv run python ./scripts/train.py
pipenv run python ./scripts/predict.py
```
