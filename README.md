[![CircleCI](https://circleci.com/gh/ClaireLee22/Operationalize-a-Machine-Learning-Microservice-API.svg?style=svg)](https://circleci.com/gh/ClaireLee22/Operationalize-a-Machine-Learning-Microservice-API)
# Operationalize a Machine Learning Microservice API
Microservice Project [Udacity Cloud DevOps Engineer Nanodegree]

## Project Overview

The project's goal is to operationalize a machine learning microservice using kubernetes. The service serves out predictions about housing prices through API. The model has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access.

### Project Tasks

Pproject's goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications. Project's tasks:
* Test project code using linting;
* Complete a Dockerfile to containerize this application;
* Deploy containerized application using Docker and make a prediction;
* Improve the log statements in the source code for this application;
* Configure Kubernetes and create a Kubernetes cluster;
* Deploy a container using Kubernetes and make a prediction;
* Upload a complete Github repo with CircleCI to indicate that code has been tested.

You can find a detailed [project rubric, here](https://review.udacity.com/#!/rubrics/2576/view).

**The final implementation of the project will showcase your abilities to operationalize production microservices.**

---

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
