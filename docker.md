---
marp: true
theme: default
# class:
#   - invert
#   - lead
---
Docker Getting Started

![bg left](https://galaxyproject.github.io/training-material/topics/admin/images/docker_whale.png)
<!-- ![bg right](https://images.unsplash.com/photo-1492313987647-28951c053899?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D) -->

<!-- #![bg ](path/to/your/background-image.jpg) -->
---
# Introduction to Docker and Containerization
**Leveraging Docker Labs for Hands-On Learning**  
Gokul Dhamodaran
21-Jul-2024

---

## Agenda
1. Introduction to Docker
2. Understanding Containerization
3. Key Docker Concepts
4. Docker Labs Overview
5. Q&A

---

## Introduction to Docker
**What is Docker?**
- A platform for developing, shipping, and running applications in containers.
- Ensures that software runs consistently across different computing environments.

**Why Use Docker?**
- Simplifies application deployment.
- Increases scalability and efficiency.
- Enhances DevOps practices.

---

## Understanding Containerization
**What is Containerization?**
- A lightweight form of virtualization.
- Packages an application and its dependencies into a container.

**Benefits of Containerization**
- Consistency: "Works on my machine" problem solved.
- Isolation: Each container runs in its own environment.
- Efficiency: Uses fewer resources than traditional VMs.

---

## Key Docker Concepts
**Docker Images**
- Read-only templates used to create containers.

**Docker Containers**
- Instances of Docker images running as isolated processes.

**Dockerfile**
- A script containing instructions to build a Docker image.

**Docker Hub**
- A cloud-based repository for finding and sharing Docker images.

---

## Docker Architecture
**Components**
- Docker Client: The CLI used to interact with Docker.
- Docker Daemon: The service running on the host machine.
- Docker Registry: Stores Docker images (Docker Hub).

**How it Works**
- The client sends commands to the daemon to build, run, and manage containers.

---

## Docker Labs Overview
**What is Docker Labs?**
- A collection of tutorials, labs, and resources for learning Docker.

**Why Use Docker Labs?**
- Hands-on learning experience.
- Step-by-step instructions for various Docker use cases.
- Covers beginner to advanced topics.

---

## Getting Started with Docker Labs
**Accessing Docker Labs**
- Visit the Docker Labs GitHub repository.
- Explore available labs and tutorials.

**Example Labs**
- Getting Started with Docker
- Building and Running Your First Docker Container
- Docker for Developers

---

## Practical Example
**Demo: Building a Simple Docker Container**
1. Create a Dockerfile.
2. Build a Docker Image.
3. Run a Docker Container.

**Link to Docker Labs**
- Include a link to the specific lab used in the demo.

---

## Best Practices
**Keep Images Lightweight**
- Minimize the number of layers and dependencies.

**Use Official Images**
- Base your images on official Docker images when possible.

**Automate Builds**
- Use CI/CD pipelines to automate the building and deployment of Docker containers.

---

## Resources and Further Learning
**Official Docker Documentation**
- [docs.docker.com](https://docs.docker.com/)

**Docker Labs GitHub**
- [github.com/docker/labs](https://github.com/docker/labs)

**Online Courses**
- Links to relevant courses on platforms like Udemy, Coursera, etc.

---

## Q&A
**Questions?**
- Open the floor for any questions from the team.

**Discussion**
- Encourage discussion and sharing of experiences with Docker.

---

## Thank You
**Contact Information**
- Your email or other contact details.

**Closing Remarks**
- Encourage the team to explore Docker further and leverage Docker Labs for hands-on practice.
