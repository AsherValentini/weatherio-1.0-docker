# WeatherIO Docker Container

This repository contains the Docker containerization setup for the WeatherIO application version 1.0.

##Build the Docker Image
To build the Docker image, run:
```bash
docker build -t weatherio .
```

##Run the Docker Container
To run the docker container:
```bash
docker run -d --name weatherio-container weatherio
```
##Access the Application
WeatherIO will be running inside the container. Use docker exec to interact if needed.

##Repo Structure
1.  app/: Contains the application source code for weatherio-1.0
2.  DockerFile: Defines the container setup.
3.  requirements.txt: Specifies the Python dependencies.
4.  .dockerignore: Excludes unnessary files from the docker build context

