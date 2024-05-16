# Experiment Tracking

## Important concepts

- ML experiment: process of building an ML model
- Experiment run: each trial in an ML experiment
- Run artifact: any file that is associated with an ML run
- Experiment metadata

## What's experiment tracking?

Experiment tracking is the process of keeping track of all the relevant information from an ML experiment, which includes : source code, environment, data, model, hyperparameters, metrics, *etc.*.

## Why is experiment tracking is important?

In general, because of 3 main reasons:
- Reproductibility
- Organization
- Optimization

## Which tools ?

## Spreadsheet

Tracking experiment in spreadsheets is a pretty simple way of tracking experiments but this approach is error prone; the format may not be standard and this approach is not very visible and not good for collaboration. 

### MLFlow

MLFlow is an open source platform for the machine learning lifecycle. In practice, it's just a Python package that can be installed with pip, and it contains four main modules:
- **Tracking**
- Models
- **Model Registry**
- Projects

The MLFlow Tracking module allows you to organize your experiments into runs, and to keep track of parameters (which includes hyperparameters and any other parameters such as the path of the training dataset), metrics, metadata, artifacts and models. Along with this information, MLFlow automatically logs extra information about the run: source code, version of the code (git commit), start and end time, author.

```bash

# command to create a storage for launching backend
mlflow ui --backend-store-uri sqlite:///mlflow.db
```