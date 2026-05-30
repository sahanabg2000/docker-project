# Docker Website Deployment Project

## Project Overview

This project demonstrates how to deploy a simple website using Docker on an AWS EC2 instance.

The website is containerized using Docker and served through an Nginx web server.

## Technologies Used

- AWS EC2
- Ubuntu Linux
- Docker
- Nginx
- Git
- GitHub

## Project Structure

docker-project/
├── Dockerfile
├── index.html
└── README.md

## Docker Commands Used

Build Image:

docker build -t sahana-website .

Run Container:

docker run -d -p 80:80 --name sahana-container sahana-website

View Running Containers:

docker ps

View Images:

docker images

## Output

The website is accessible through the EC2 public IP address.

Example Page:

Hello from Sahana's Docker Project!
This website is running inside a Docker container.

## Author

Sahana Gondi
