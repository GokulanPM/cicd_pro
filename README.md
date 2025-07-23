CI/CD Pipeline Project using Jenkins, Docker, and AWS

Summary
▸This project demonstrates how to build and deploy a fully automated CI/CD pipeline using Jenkins, Docker, and AWS EC2. It simulates a real-world DevOps workflow, where code changes are automatically built, containerized, and deployed to a cloud server. The goal is to showcase strong understanding and hands-on experience in continuous integration, continuous deployment, containerization, and cloud infrastructure management.

Features
▸Automates the build, test, and deployment process using Jenkins
▸Uses Docker to containerize a Python Flask application
▸Stores Docker images in Docker Hub for reuse and scaling
▸Automatically deploys updated containers to an AWS EC2 instance
▸Implements a complete CI/CD workflow with minimal manual steps

Architecture Overview
▸Developer pushes code to a GitHub repository.
▸Jenkins (running on EC2) pulls the latest code.
▸Jenkins builds a Docker image from the code.
▸Jenkins pushes the image to Docker Hub.
▸Jenkins uses Docker Compose to deploy the containerized app to an EC2 instance.

Technology Stack
▸ Jenkins – For automating the CI/CD pipeline
▸ Docker – For containerizing the Flask web application
▸ Docker Hub – For storing and sharing Docker images
▸ AWS EC2 – To host the Jenkins server and deploy the application
▸ Git & GitHub – For version control and source code management
▸ Flask (Python) – Lightweight web application framework for the sample app
▸ Docker Compose – For deploying multi-container apps in production
▸ Linux (Ubuntu) – For the base EC2 environment and system-level tasks

To test locally:
1. Clone the repo
2. Run: docker build -t myapp .
3. Run: docker run -p 5000:5000 myapp

What I Learned
▸Built a real-world DevOps pipeline with continuous integration and deployment
▸Gained experience in writing Dockerfiles and Jenkinsfiles
▸Learned how to manage cloud infrastructure using AWS EC2
▸Used Docker Compose for deploying multi-container apps
▸Understood the role of GitHub in source control automation
▸Practiced writing clean, well-documented code and automation scripts

Author
Created by Gokulan PM
▸GitHub: https://github.com/GokulanPM
▸LinkedIn: https://www.linkedin.com/in/gokulanpm
