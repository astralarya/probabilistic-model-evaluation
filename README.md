# Probabilistic Model Evaluation with Tensorflow

When using deep learning models in production,
we do not have the luxury of having access to ground-truth.
However, it may be feasable to integrate a human domain expert
into production workflows.

In order to maximize throughput,
we must be selective about when we alert our human expert.
If we can understand the reliability of our model predictions
as a function of its self-reported confidence,
we can use this to guide business logic in our application.

## Setup

Install [pipenv](https://pipenv-es.readthedocs.io/es/stable/),
then install dependencies:
```bash
pipenv install
```

## Usage

Activate pipenv and run JupyterLab:
```bash
pipenv shell
jupyter-lab
```