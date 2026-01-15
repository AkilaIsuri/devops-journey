# Docker – Core Concepts

## What is a container?

A container is a lightweight, deployable unit that packages an application
together with its dependencies and environment variables.

A container is a **running instance of a Docker image** and runs in an
isolated environment, ensuring the application behaves the same across
different systems.


## The difference between containers and VM

Containers and VMs are both used to isolate applications but they have major differencs.

Containers virtualize the operating system. They share the host operating system making it light weight and fast to start. Therefore containers provide less isolation and security. Containers are portable and they can run on a a system with a compatible operating system. Each container includes dependencies and application. They are efficient in resource usage. 

Virtuale machines virtualize the hardware. Each VM includes a guest OS, application and dependensies. They run on the physical infrastructure using a hypervisor. So they are not efficient in resource utilizaton. VMs have a higher level of security and isolation as they are having their own operatiog systems. They are not compatible as they ned a hypervisor to operate. And also they are heavy weighted.

## Why containers are light weighted?

They use containerization, where they are allowed to share the host operating system's kernel and libraries while providing isolation for the application and dependencies.


| Aspect         | Virtual Machines | Containers |
| -------------- | ---------------- | ---------- |
| Virtualization | Hardware-level   | OS-level   |
| OS per app     | Yes              | No         |
| Startup time   | Minutes          | Seconds    |
| Resource usage | High             | Low        |
| Portability    | Limited          | High       |

## What is Docker?

Docker is a containerization platform that allows applications
to be packaged together with all required dependencies and
run consistently across environments.

## Why Docker?
As an Operational Engineer, I am learning Docker to:
- Eliminate "works on my machine" problems
- Standardize deployments
- Support CI/CD pipelines
- Prepare for Kubernetes and AIOps

## Key Docker Concepts

### Image
A Docker image is a lightweight, immutable template that
contains the application code, runtime, libraries, and
dependencies.

### Container
A container is a running instance of a Docker image.
Containers are isolated, lightweight, and fast to start.

### Dockerfile
A Dockerfile is a text file that defines how a Docker image
is built.

### Docker Engine
Docker Engine is the core service that builds and runs
containers.

### Image vs Container
- Image → Blueprint
- Container → Running application

## Learning Approach
This repository starts from Docker fundamentals and
gradually progresses toward DevOps and AIOps concepts.



