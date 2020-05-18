
# HR Stay or Leave

  

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/AkashSDas)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/AkashSDas)

[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE)

  
  

## Table of contents

  

*  [About](#about)

* [Technologies Used](#technologies-used)

* [Results of the Project](#results-of-the-project)

*  [Installation](#installation)

*  [License](#license)

  
  

## About

> Using the imbalanced dataset, first balancing the dataset using `SMOT` and then using `Recursive Featrue Elimination` to find relevant features that tells that whether the employee will `stay` or `leave` the company using this `preprocessed` data using `cross validation` and `parameter tuning` to create a `machine learning` model that can predict whether the employee will `stay` or `leave` the company. At last creating a `pipeline`. Also viewing at `Classification Matrix` to look at scores of `recall`, `precision` and `f1-score` and `ROC Curve` to verify whether the model is works fine or not.

## Technologies Used
  
> [![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/) is used as Programming Language.

>  `Numpy` and `Pandas` are used to work with the data.

> `Matplotlib` and `Seaborn` is used to visualise the results.

> `imblearn` is used to apply `SMOT` algorithm so that we can balance the imbalance dataset.

>  `statsmodels` package to do `Recursive Feature Elimination` to find `relevant features`.

> `Sciki-learn` is used for data preprocessing, creating machine learning model and evaluating it, thus creating a pipeline.

> `Pipenv` is the virtual environment used for the project. `Jupyter Notebook` is used to for the entire data science and machine learning life cycle.

## Results of the Project

#### Imbalance Data Count

![Imbalance Data Count](https://github.com/AkashSDas/HR-Stay-or-Leave/blob/master/project-results-images/count.png)

#### Correlation Matrix

![Correlation Matrix](https://github.com/AkashSDas/HR-Stay-or-Leave/blob/master/project-results-images/correlation-matrix.png)

#### Recursive Feature Elimination Results

![Recursive Feature Elimination Results](https://github.com/AkashSDas/HR-Stay-or-Leave/blob/master/project-results-images/rfe.png)

#### Cross Validation Scores

![Cross Validation Scores](https://github.com/AkashSDas/HR-Stay-or-Leave/blob/master/project-results-images/cross.png)

#### Learning Curve 

![Learning Curve](https://github.com/AkashSDas/HR-Stay-or-Leave/blob/master/project-results-images/learning-curve.png)

####  Metrics Scores

![Metrics Scores](https://github.com/AkashSDas/HR-Stay-or-Leave/blob/master/project-results-images/metrics-scores.png)

#### Confusion Matrix

```python
               precision    recall  f1-score   support

           0       0.95      0.95      0.95      3408
           1       0.84      0.84      0.84      1092

    accuracy                           0.92      4500
   macro avg       0.89      0.89      0.89      4500
weighted avg       0.92      0.92      0.92      4500
```

![Confusion Matrix](https://github.com/AkashSDas/HR-Stay-or-Leave/blob/master/project-results-images/confusion-matrix.png)

#### ROC Curve

![ROC Curve](https://github.com/AkashSDas/HR-Stay-or-Leave/blob/master/project-results-images/roc.png)

## Installation

  

It is highly **recommended** to use **`virtual environment`** for this project to avoid any issues related to dependencies.

  

Here **`pipenv`** is used for this project.

  

There is a **`requirements.txt`** file in `'HR-Stay-or-Leave'/requirements.txt` which has all the dependencies for this project.

  

- First, start by closing the repository

  

```bash
git clone https://github.com/AkashSDas/HR-Stay-or-Leave
```

  

- Start by installing **`pipenv`** if you don't have it

```bash
pip install pipenv
```

  

- Once installed, access the venv folder inside the project folder

```bash
cd  'HR-Stay-or-Leave'/venv/
```

  

- Create the virtual environment

```bash
pipenv install
```

The **Pipfile** of the project must be for creating replicating project's virtual environment.

  

This will install all the dependencies and create a **Pipfile.lock** (this should not be altered).

  

- Enable the virtual environment

```bash
pipenv shell
```
- dataset, jupyter notebook and model are in `'HR-Stay-or-Leave'/venv/src` folder.
```bash
cd src/
```

  

- To start/view the jupyter notebook

```bash
jupyter noterbook
```

  

This will open a webpage in the browser from there you can click on notebook.ipynb to view it.
  

## License

  

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.
