# CI/CD Tools and Practices Final Project

## Project Overview
This project demonstrates Continuous Integration and Continuous Delivery (CI/CD) practices for a Python Flask application using GitHub Actions and Tekton.

## Technologies Used
- Python
- Flask
- Git and GitHub
- GitHub Actions
- Tekton Pipelines
- Docker
- OpenShift
- Flake8 for code linting
- Nose for unit testing

## Application
The project contains a Python Flask service and automated checks to help ensure code quality and application reliability.

## Continuous Integration
The CI workflow includes:
- Checking out the source code
- Installing project dependencies
- Linting Python code with Flake8
- Running unit tests with Nose

## Tekton Workflows
The `.tekton/` directory contains Tekton task definitions used for the CI/CD pipeline.

## Running the Application
Install the dependencies listed in `requirements.txt` and follow the repository's application configuration to run the service.

## Project Purpose
The purpose of this project is to practice automating software quality checks and preparing an application for container-based deployment.
