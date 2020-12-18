# [Project 5 (Capstone): Operationalizing a Machine Learning Microservice API](https://github.com/NawfalTachfine/DevOpsCapstone)

## Project Scope
The project automatically builds and deploys a machine learning prediction web service with 3 replicas on a cloud kubernetes cluster.

## Pipeline Setup
+ [Code Repository](https://github.com/NawfalTachfine/DevOpsCapstone)
+ [Image Repository](https://hub.docker.com/repository/docker/nawfaltachfine/ml-microservice)

## Automatic Container Builds
+ Continuous integration: code linting ([not working](assets/1.linter_error.pdf) / [working](assets/2.linter_fix.pdf))
+ The *Docker* image is automatically [built and pushed to the repository](assets/3.successful_deployment.pdf).

## Infrastructure as Code and Rolling Deployments
+ The cluster is provisioned using the *CloudFormation* templates in the `eks` directory.
+ [Rolling updates example](assets/3.successful_deployment.pdf)
