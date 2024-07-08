# Node.js-Microservice-with-Docker
# Node.js Microservice with Docker

A simple Node.js microservice using Express, containerized with Docker. This project demonstrates how to set up, build, and run a Node.js application inside a Docker container.

## Features

- Simple Node.js application using Express
- Dockerfile for containerization
- .gitignore configuration to exclude unnecessary files

## Prerequisites

- [Node.js](https://nodejs.org/)
- [Docker](https://www.docker.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Install Dependencies
npm install

# Run the Application Locally
node app.js

Navigate to http://localhost:3000 to see the "Hello World!" message.

# Docker
# Build the Docker Image
docker build -t my-microservice .

# Run the Docker Container
docker run -p 3000:3000 my-microservice

Navigate to http://localhost:3000 to see the "Hello World!" message.

