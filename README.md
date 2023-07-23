# Portfolio Dockerization with Docker Compose 🐳


This repository contains the Dockerized version of my portfolio website, built using Docker and Docker Compose. The project aims to simplify the setup and deployment process, making it easy for others to run my portfolio locally or deploy it to a server.

Features:

Dockerization: The portfolio application, including its dependencies and runtime environment, is containerized using Docker. This ensures consistency across different environments and simplifies the deployment process.

Docker Compose: The project uses Docker Compose to define and manage the multi-container setup. The docker-compose.yml file specifies the services, volumes, networks, and environment variables needed to run the application.

Simplified Setup: With Docker and Docker Compose, setting up the portfolio locally becomes straightforward. No need to worry about installing specific dependencies or configuring the environment manually.

Scalable and Isolated: The application is designed to run as isolated containers, allowing for easy scalability and improved security.

Deployment:
To deploy the portfolio website, simply clone this repository and execute a few Docker commands. The docker-compose.yml file contains all the necessary configurations, including port mappings and environment variables.

Step-by-step guide:

Clone this repository: git clone https://github.com/yourusername/Portfolio-Dockerization.git

Navigate to the project directory: cd Portfolio-Dockerization

Customize the environment variables in the docker-compose.yml file, such as the website title, database connection strings, etc.

Build the Docker images: docker-compose build

Start the containers: docker-compose up -d

That's it! Your portfolio website should now be up and running. Visit http://localhost:8000 in your web browser to view the website. You can also customize the port mapping in the docker-compose.yml file.

Feel free to explore the Dockerfile and other configuration files to understand how the Docker image is created and how the services are orchestrated.

Happy Dockerizing! 🚀
