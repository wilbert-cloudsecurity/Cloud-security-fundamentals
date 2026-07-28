# Docker Fundamentals

## What Docker Is
Docker is a containerization platform that packages applications and their dependencies into lightweight, portable containers that run consistently across different environments.

## Why Docker Matters
Containers simplify application deployment, improve development consistency, and provide the foundation for modern DevOps, cloud-native applications, and Kubernetes.

---

# Core Concepts

## Containers
- Lightweight isolated environments that share the host operating system kernel
- Start quickly and consume fewer resources than virtual machines
- Package applications together with their dependencies

## Images
- Read-only templates used to create containers
- Built from Dockerfiles using layered architecture
- Reusable and versioned for consistent deployments

## Dockerfile
- **FROM** → Defines the base image
- **COPY** → Copies application files into the image
- **EXPOSE** → Documents application ports
- **CMD** → Specifies the default command executed by the container

## Volumes
- Provide persistent storage independent of the container lifecycle
- Preserve application data after containers are removed
- Commonly used for databases and application data

## Networking
- Containers communicate through Docker networks
- Bridge networks provide isolated communication
- Built-in DNS allows communication using container names

## Docker Compose
- Defines multi-container applications using YAML
- Manages containers, networks, and volumes together
- Enables reproducible environments with a single command

---

# What I Practiced

- Installed Docker Engine on Linux
- Configured Docker permissions for non-root usage
- Managed the complete container lifecycle using Docker CLI
- Built custom images using Dockerfiles
- Deployed an Nginx web server with a custom HTML page
- Created persistent PostgreSQL storage using Docker Volumes
- Connected multiple containers through a custom Bridge network
- Verified communication between containers using Docker DNS
- Automated infrastructure using Docker Compose
- Practiced container inspection and troubleshooting
- Explored security best practices such as non-root execution and lightweight Alpine images
- Reviewed deployment approaches for publishing containerized applications

---

## Why It Matters
Docker is a foundational technology for modern cloud infrastructure, enabling portable applications, reproducible environments, and scalable deployments. Mastering Docker provides the skills required before moving into Kubernetes and production container orchestration.
