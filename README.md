# Face-Classification
Age, Gender and Race Face Classification

## Download dataset

Create folder 'data' and put dataset age_gender_race.csv inside. Dataset can be downloaded [here](https://drive.google.com/drive/folders/1Lnp4u1mNNQ6Gqc-JDW9OmniOnNV65y43?usp=sharing).

Create folder 'models' and put pretrained models inside. Download them [here](https://drive.google.com/drive/folders/16-EhiXckrL2wcrBuGXp9R2EPLX966_VQ?usp=sharing)

## Set up project

### Online:

The notebooks can be previewed directly on GitHub without installing any additional software.

### Locally:

+ Recommend python version: `3.6+`
+ Full list of dependencies can be found at `requirements.txt`

### Install dependencies
+ Create virtual environment and install dependencies with the following command:
```
virtualenv --python=/usr/bin/python3.8 venv
source venv/bin/activate
pip install -r requirements.txt
```

+ Or install using [pipenv](https://pypi.org/project/pipenv/). Inside the directory, run:

```
pipenv install
```

## Start Jupyter Notebook:
Make sure jupyter is using venv python interpreter.

```
jupyter lab
```
