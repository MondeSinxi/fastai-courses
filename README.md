# fastai-courses
The repo contains a set of notebooks obtained from following the fast ai course

## Getting started

### Setting up your Python environment

Setup the virtual environemnt 

`python -m venv env`

Activate the environment

`source env/bin/activate`

Install the requirements

`pip install -r requirements.txt`

### Getting started on Google Collab

The notebooks are meant to be run on [Google collab](https://colab.research.google.com/notebooks/welcome.ipynb#recent=true) as it has free access to GPUs, which we will need in order to complete tasks in the course.
Keeping that in mind, make sure that you have access to the data wherever the notebook is being hosted. Google collab can pull notebooks from Github, which becomes very useful for managing working in different environments (which I often do)

A lot of the data is hosted on [Kaggle](https://www.kaggle.com). This will probably be the centre of data science life. What is Kaggle? 

> Kaggle is an online community of data scientists and machine learners, owned by Google LLC. Kaggle allows users to find and publish data sets, explore and build models in a web-based data-science environment, work with other data scientists and machine learning engineers, and enter competitions to solve data science challenges 

Sign up and register to obtain an API token to be able to easily download datasets and publish results for competitions.

## Introduction to Random Forests (Bull Book for Bulldozers)
Create random forrest to create solutions to the [Bull Book for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers) Kaggle competion.
The goal of the contest is to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration.
