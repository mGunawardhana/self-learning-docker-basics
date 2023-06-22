## What is Docker ?

![Docker logo2_](https://github.com/mGunawardhana/self-learning-docker-basics/assets/100486080/761f3a90-6ec7-49af-ba56-5d401ce85fe8)

Docker is an open-source platform that allows you to automate the deployment, scaling, and management of applications using containerization. Containers are lightweight, isolated environments that package an application along with its dependencies and configurations, ensuring consistency and reproducibility across different computing environments.

Here are a few key concepts related to Docker:

1. **Containers**: Containers are self-contained units that encapsulate an application and its dependencies. They provide a consistent and isolated environment for running applications, regardless of the underlying infrastructure.

2. **Images**: Docker images are read-only templates used to create containers. An image contains everything needed to run an application, including the code, runtime, system libraries, and dependencies. Images are built from a set of instructions called a Dockerfile.

3. **Dockerfile**: A Dockerfile is a text file that defines the steps to build a Docker image. It includes instructions to install dependencies, copy files, set environment variables, and specify the commands to run when the container starts.

4. **Containerization**: Containerization is the process of creating and managing containers. Docker provides a runtime environment that enables containers to run on any host system without worrying about compatibility issues.

5. **Docker Engine**: Docker Engine is the runtime that runs and manages containers. It consists of a server and a command-line interface (CLI) client. The server, also known as the Docker daemon, listens for Docker API requests and manages container images and running containers.

6. **Docker Hub**: Docker Hub is a public registry that allows you to store and share Docker images. It provides a vast collection of pre-built images that can be used as a base for your applications.

7. **Docker Compose**: Docker Compose is a tool that allows you to define and manage multi-container applications. It uses a YAML file to specify the services, networks, and volumes required for your application's components.

Docker has gained popularity due to its ability to simplify application deployment, improve scalability, and enable consistent development and production environments. It has become a standard tool in the software development and DevOps communities.
