# Build CI/CD Pipelines, Monitoring & Logging
This is one of the project in Udacity Cloud DevOps Engineer Nanodegree.

## Project Overview
In this project, you’ll learn the process of taking software from source code to deployment and beyond. You’ll learn about automated testing, choosing the right deployment strategy for your business needs and deploying an appropriate CI/CD pipeline.

## Project Files

- `screenshots`: This folder contains all screenshots taken during creation of this project.
- `Jenkinsfile`: This file contains the steps of CICD pipeline of application.
- `index.html`: This is main html file of application.

## Project Setup

- Create an IAM user with permissions shown in `\screenshots\screenshot-01.PNG`.
- Create an EC2 instance.
- Install Jenkins and tidy on that instance.
- Create a S3 bucket and give the same name of S3 bucket in `Jenkinsfile` also.
- Enable static website hosting on that S3 bucket properties.
- Add AWS credentials in Jenkins.
- Create one pipeline in Jenkins using the `Jenkinsfile` given in this repo.
- On successful completion of pipeline, open the URL of S3 bucket static website and you will see the application on that URL.
