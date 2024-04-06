# DevOps - Automated Builds Pushing to Dockerhub

This repository serves as an introduction to setting up Continuous Integration/Continuous Deployment (CI/CD) pipelines for automating the testing, building, and pushing of Docker images to Docker Hub.

To get started with setting up your own CI/CD pipeline, follow these steps:
1. **Create a GitHub Repository**: Create a new GitHub repository from scratch based on the instructions provided in the videos.

2. **Set Up GitHub Actions**: Configure GitHub Actions workflow file (e.g., `.github/workflows/main.yml`) to define the CI/CD pipeline. Make sure to separate jobs and use dependencies (`needs`) to ensure the test job completes before the build and push job.

3. **Test, Build, and Push to Docker Hub**: Commit your changes to the repository and observe GitHub Actions running the defined workflow. Once the workflow completes successfully, verify that the Docker image is pushed to your Docker Hub account.
