# docker-challenge-midterm

This repository contains my solutions for two Docker challenges as part of my midterm/final project. The challenges focus on containerizing applications using Docker and Docker Compose.

## Challenge 1: Simple Static Page Server

### Objective
Create a Docker container to serve a basic static web page using NGinx.

### Steps Taken
1. **Project Setup**:
   - Created a `challenge1` folder structure.
   - Developed an `index.html` file with personal details inside the `public` folder.

2. **Docker Setup**:
   - Implemented a `Dockerfile` to build an NGinx container.
   - Configured NGinx to serve content from the `public` folder.

3. **Execution**:
   - Built the Docker image and ran the container.
   - Accessed the webpage at `http://localhost:8080/` to verify functionality.

### Outcome
Successfully deployed a static web page using Docker and NGinx, demonstrating fundamental Docker containerization concepts.

---

## Challenge 2: NodeJS Application

### Objective
Containerize a NodeJS application and integrate it with NGinx using Docker Compose.

### Steps Taken
1. **Project Setup**:
   - Created a `challenge2` directory.
   - Extracted the NodeJS application files into `challenge2`.

2. **Docker Setup**:
   - Developed a `Dockerfile` to build the NodeJS application container.
   - Configured NGinx in `docker-compose.yml` to proxy requests to the NodeJS server.

3. **Execution**:
   - Utilized Docker Compose to build and orchestrate NGinx and NodeJS containers.
   - Tested endpoints at `http://localhost:8080/api/books` and `/api/books/1` to validate functionality.

### Outcome
Successfully containerized a NodeJS application and integrated it with NGinx using Docker Compose, demonstrating advanced Docker orchestration capabilities.
