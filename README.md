# devops-qoala-assignment-Ansh_Gangola_21ucc018

DevOps Internship Challenge

This repository contains a Dockerized web application built with Python and Nginx. The application demonstrates a simple setup of a Flask application behind an Nginx reverse proxy using Docker Compose.

Table of Contents:

    .Project Structure

    .Prerequisites

    .Setup Instructions

    .Running the Application

    .Screenshots

    .Report

    .Issues Identified and Resolution

## Project Structure
```
.
├── docker-compose.yml       # Docker Compose file to manage multi-container application
├── nginx/
│   ├── Dockerfile           # Dockerfile for Nginx container
│   └── nginx.conf           # Nginx configuration file
├── python_app/
│   ├── Dockerfile           # Dockerfile for Python Flask container
│   └── app.py               # Python application code (Flask app)
└── README.md                # Documentation for the application
```


Prerequisites:

Ensure you have the following installed:

    .Docker (v20+ recommended)
    .Docker Compose (v1.29+ recommended)
    .A web browser to view the application

Setup Instructions:

1.  Clone the Repository
    git clone <repository-url>
    cd devops-internship-challenge

2.  Build Docker Images
    Build each Docker image defined in the docker-compose.yml file.

        docker-compose build

3.  Start the Containers

    Launch the containers using Docker Compose.

        docker-compose up

4.  Access the Application

    Once the containers are running, open a web browser and go to http://localhost to view the application.

Running the Application:

The docker-compose.yml file will launch two containers:

    1. Python Flask Application (on port 8000 internally)
    2. Nginx (serving as a reverse proxy to the Flask app on port 80)

To stop the application:

    docker-compose down

Screenshots:

    Screenshot of the application running in the browser.
    Screenshot of logs from the Flask container to confirm it’s running.

Issues Identified and Resolution:
Report attached along is summarizing all the issues identified and resolutions made.
