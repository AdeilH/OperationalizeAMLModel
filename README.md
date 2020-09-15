[![CircleCI](https://circleci.com/gh/AdeilH/OperationalizeAMLModel.svg?style=svg)](https://circleci.com/gh/AdeilH/OperationalizeAMLModel)

## Project Overview

In this project the goal is to use some scripts to deploy docker containers and also to use
kubernetes and how it works in orchestrating the containers.

The application has been provided in Python that is used for predicting housing prices. 

The aim is to learn how to operationalize flask based python apps in docker. 

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

1. `minikube start`
2. Run Kubernetes. 
