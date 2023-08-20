# flask_docker

This repository contains a simple Flask app that is deployed using Docker. The app provides a basic web interface and demonstrates how to containerize a Flask application using Docker.

1. Navigate to the project directory after cloning the ropo:

```
cd flask-docker-app
```
2. Build the Docker image using the provided Dockerfile:

```
docker build -t flask-app .
```
3. Run the Docker container:

```
docker run -p 5000:5000 flask-app
```

4. Open your web browser and go to http://localhost:5000 to access the Flask app.
