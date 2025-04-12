# SIT323-2025-Prac5P - Dockerised Node.js Web Application

This repository contains a simple Node.js web application that has been containerised using Docker and Docker Compose as part of the SIT323/SIT737 Cloud-Native Application Development unit.

## 📦 Project Overview

- This project demonstrates the containerisation of a basic Express.js web server using Docker.
- Docker Compose is used to manage and run the containerised app.
- The app listens on port `3000` and responds with a simple message.

## 🛠️ Technologies Used

- Node.js
- Express.js
- Docker
- Docker Compose

## 📁 Folder Structure

app.js
A basic Node.js Express server that returns a simple response on the root route.

Dockerfile
Defines the Docker image, including base image, dependencies, and run instructions.

docker-compose.yml
Manages the container service and maps the app's port 3000 to the local system.

package.json
Contains the Node.js project configuration and dependencies.
