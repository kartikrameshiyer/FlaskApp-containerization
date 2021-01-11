# FlaskApp-containerization

## Overal Build [![CircleCI](https://circleci.com/gh/kartikrameshiyer/project-ml-microservice-kubernetes.svg?style=svg)](https://app.circleci.com/pipelines/github/kartikrameshiyer)

[![CircleCI](https://circleci.com/gh/kartikrameshiyer/project-ml-microservice-kubernetes.svg?style=shield)](https://app.circleci.com/pipelines/github/kartikrameshiyer)

## Project Overview

The project is a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing). We need to operationalize a Python flask app—in a provided file, `app.py`—that serves out predictions (inference) about housing prices through API calls.
This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

### Project Tasks

Our project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications. In this project you will:

- Test your project code using linting
- Complete a Dockerfile to containerize this application
- Upload a complete Github repo with CircleCI to indicate that your code has been tested



---

## Setup the Environment

- Create a virtualenv and activate it
- Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone: `python app.py`
2. Run in Docker: `./run_docker.sh`
