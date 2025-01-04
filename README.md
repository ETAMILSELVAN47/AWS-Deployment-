# 1.Flask App Deployment in AWS using Docker

This repository contains the steps for deploying a Flask application on AWS using Docker. The deployment pipeline involves the following services:

- **GitHub → ECR → EC2**

The process includes pushing the Dockerized Flask app from GitHub to AWS Elastic Container Registry (ECR), then deploying it to an EC2 instance for production use.

### Overview

1. **GitHub**: Source code repository for the Flask app.
2. **ECR (Elastic Container Registry)**: Store and manage Docker images.
3. **EC2 (Elastic Compute Cloud)**: Host the Flask app using Docker on an EC2 instance.

