[![CircleCI](https://circleci.com/gh/AdeilH/OperationalizeAMLModel.svg?style=svg)](https://circleci.com/gh/AdeilH/OperationalizeAMLModel)

## Project Overview

In this project the goal is to use some scripts to deploy docker containers and also to use
kubernetes and how it works in orchestrating the containers.

The application has been provided in Python that is used for predicting housing prices. 

The aim is to learn how to operationalize flask based python apps in docker. 

### Project Tasks

Your project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications. In this project you will:
* Test your project code using linting
* Complete a Dockerfile to containerize this application
* Deploy your containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate that your code has been tested

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

1. `minikube start`
2. Run Kubernetes. 
