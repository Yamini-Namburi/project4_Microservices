# project4_MicroserviceProject Tasks:
This project goal is to operationalize this working, machine learning microservice using kubernetes, which is an open-source system for automating the management of containerized applications. In this project you will:

Test your project code using linting
Complete a Dockerfile to containerize this application
Deploy your containerized application using Docker and make a prediction
Improve the log statements in the source code for this application
Configure Kubernetes and create a Kubernetes cluster
Deploy a container using Kubernetes and make a prediction
Upload a complete Github repo with CircleCI to indicate that your code has been tested


The files included are:
* /.circleci : CircleCI configuration file for running the tests
* /model_data : Housing model data
* /output_txt_files : Log of Output 
* Dockerfile : Dockerfile for building the image 
* Makefile : includes instructions on environment setup and lint tests
* app.py : Python flask app that serves out predictions (inference) about housing prices through API calls
* make_prediction.sh : Send a request to the Python flask app to get a prediction, for localhost 
* requirements.txt : Install any dependencies 
* run_docker.sh : file to be able to get Docker running, locally
* run_kubernetes.sh : file to run the app in kubernetes
* upload_docker.sh : file to upload the image to docker


Creation and activation of the environment
Docker installation
Lints checks with hadolint and pylint
Installation of Kubernetes and Minikube
Dockerfile
Dockerfile configuration
Run a Container & Make a Prediction
Logging in the docker_out.txt file
Kubernetes
Configure Kubernetes to Run Locally
Deploy with Kubernetes
Savings Output logs in the file kubernetes.out.txt
CircleCI Integration
This repository has been verified with CircleCI

Run the project:
* Please follow to steps of screenshot in Images-of-result-deploy folders