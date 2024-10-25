
# Flask App with Jenkins Pipeline

This project is a Python Flask web application that integrates with Jenkins for CI/CD. The app is containerized using Docker and has unit tests.

## This pipeline has three stages:

Build: It builds the Docker image for the Flask app.
Test: It runs the unit tests using pytest.
Deploy: It deploys the Flask app by running it in a Docker container on port 5000.