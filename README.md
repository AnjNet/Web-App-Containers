# Web App Containerized with Docker and Podman

This is a  HTML/CSS/JavaScript web app served using NGINX and containerized using Docker and Podman on Windows.

## Tools
- Docker Desktop for Windows
- Podman for Windows
- NGINX (via Docker image)

## How to Run

### Docker

docker build -t my-web-app .
docker run -d -p 8080:80 --name webapp-docker my-web-app


### Podman

podman build -t my-web-app .
podman run -d -p 8081:80 --name webapp-podman my-web-app


## Screenshots
Check the `/screenshots/platform1/` and `/platform2/` folders for Docker and Podman setup screenshots.