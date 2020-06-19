[![CircleCI](https://circleci.com/gh/abrahamfov/ml-microservice-k8s.svg?style=svg)](https://circleci.com/gh/aabrahamfov/ml-microservice-k8s)

## Project Overview

This project is an assignment required by the Udacity's Cloud DevOps Nanodegree.

### Project Tasks

The project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications. In this project you will:
* Test your project code using linting
* Complete a Dockerfile to containerize this application
* Deploy your containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate that your code has been tested

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Python and Docker linting
* Run 'make lint' to execute the linting of these two files.
