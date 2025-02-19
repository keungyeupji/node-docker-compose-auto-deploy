# node-docker-compose-auto-deploy
# Node.js Docker Compose Auto Deploy Example

This is an example project that demonstrates how to containerize a simple Node.js application using Docker and Docker Compose, and automate the deployment process using GitHub Actions.

## Project Structure

- `app.js`: A simple Express.js server.
- `package.json`: Node.js dependencies and scripts.
- `Dockerfile`: Defines how to build the Docker image.
- `docker-compose.yml`: Configures the services for Docker Compose.
- `.github/workflows/docker-build-deploy.yml`: GitHub Actions workflow for automated Docker image building and deployment.

## How to Run Locally

1. Clone the repository:
   git clone https://github.com/your-username/node-docker-compose-auto-deploy.git
   cd node-docker-compose-auto-deploy
