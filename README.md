# Docker Nginx Website

## Project Overview

This project demonstrates how to build and run a simple website inside a Docker container using Nginx.

The website is packaged into a Docker image and deployed as a Docker container, making it portable and consistent across environments.

## Technologies Used

* Docker
* Nginx
* HTML

## Project Files

* `Dockerfile` – Instructions to build the Docker image
* `index.html` – Website content
* `.gitignore` – Excludes unnecessary files

## Docker Commands

### Build Image

docker build -t my-nginx-site .

### Run Container

docker run -d -p 8080:80 --name my-website my-nginx-site

### View Running Containers

docker ps

### Stop Container

docker stop my-website

### Start Container

docker start my-website

## Key Learning

* Docker Image vs Docker Container
* Containerisation
* Port Mapping
* Running Nginx inside Docker

## Outcome

Successfully built a Docker image, created a Docker container, and hosted a website accessible through http://localhost:8080

## Screenshots

Project screenshots are available in the screenshots folder.
