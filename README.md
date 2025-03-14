# Project Setup Guide

## Pre-requisites
Before setting up the project, ensure your system meets the following requirements:

1. **RAM:** Minimum 16GB
2. **Hard Disk:** Minimum 150GB
3. **Docker Installation:** Ensure Docker is installed and running on your system.
4. **Git Installation:** Ensure Git is installed.

## Installation Steps
Follow the steps below to set up the project:

### Step 1: Navigate to the Docker Directory
cd Project/docker

### Step 2: Start the Docker Containers
docker compose up -d

### Step 3: Add the Model to the Ollama Docker Container. Choose and add a model to the Ollama container by running the following command:
docker exec -it ollama ollama run gemma2:2b

### Step 4: Access the Web Application. Open your browser and navigate to:
http://<your-ip-address>/install

Note: Refer the InstallationDocument.pdf for more details about Admin Initial Setup, Knowledge Base - Uploading files, Creating Chatbots

If you encounter any issues, please check the logs using:
docker logs -f <container_name>
