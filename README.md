###Flask Redis Application

#Overview
  This project is a simple web application built using Flask and Redis.
  It demonstrates how to create a web service that interacts with a Redis database, handling basic data storage and retrieval.

##Technologies Used
   Flask: A lightweight WSGI web application framework for Python.
   Redis: An in-memory data structure store, used as a database, cache, and message broker.
   Docker: A platform for developing, shipping, and running applications in containers.
   Docker Compose: A tool for defining and running multi-container Docker applications.

##Prerequisites
   Before you begin, ensure you have met the following requirements:

1. Clone the Repository
    git clone  https://github.com/AditiPandey568/Docker-Compose.git
    cd composetest

3. Build and Run the Application
    You can run the application using Docker Compose. This will set up both the Flask web application and the Redis server.

##bash
    docker compose up
    This command will build the Docker images and start the containers as defined in the docker-compose.yml file.

##Application Structure
  app.py
     This is the main file where the Flask application is defined. It contains routes for handling web requests and interacts with the Redis database.

Dockerfile
 This file defines the environment for the Flask application. It specifies the base image, copies application files, installs dependencies, and sets the command to run the app.

docker-compose.yml
This file contains the configuration for running multiple services with Docker Compose. It specifies the services (web and redis), their images, ports, and dependencies.

requirements.txt
This file lists the Python dependencies needed for the application. It includes Flask and Redis libraries.

##Contributing
     Contributions are welcome! If you have suggestions for improvements, please open an issue or submit a pull request.
##License
    This project is licensed under the MIT License - see the LICENSE file for details.
