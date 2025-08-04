## 🗂️ Project Structure

### Created a monorepo named nodejs-demo-app

A Node.js backend

## 🐳 Dockerization

### Wrote a Dockerfile for the backend

Built the Docker image using:

`docker build -t nodejs-backend .`

Ran the container locally using:

`docker run -p 3000:3000 nodejs-backend`

## 🛠️ GitHub Repository

Initialized Git

Renamed repository to nodejs-demo-app

Pushed project to GitHub under the main branch

## 🤖 CI/CD with GitHub Actions

### Created GitHub Actions workflow:

`.github/workflows/docker-build.yml`

### The workflow:

Triggers on push to main

Builds the Docker image

Pushes it to Docker Hub

## 🔐 Secrets & Docker Hub Integration

### Stored the following GitHub secrets:

`DOCKER_USERNAME`

`DOCKER_PASSWORD`

Successfully integrated Docker Hub for automated image deployment.
