# OpenShift Django Deployment Script

A deployment script that creates a new Django application, creates a new GitHub repo, and deploys it to OpenShift v3 as a Docker image

This script does the following:
- Creates and activates a virtualenv
- Installs the requirements.txt
- Creates a Django Project
- Creates a Django App
- Updates the Project and App to work with Gunicorn and deployable
- Creates a new GitHub repository
- Deploys the new repository to OpenShift