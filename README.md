# Docker Lab 1 - Introduction to Docker Containerization

## Guide Questions

### 1. What role does the Dockerfile play in containerization?
A Dockerfile is like a set of instructions. It tells Docker what to do to create a container, like what files to add, what to install, and how to run the program.

### 2. Why are Docker containers lighter than virtual machines?
Docker containers are lighter because they don’t need a full operating system. They share the system of the computer they run on. Virtual machines need their own OS, so they use more space and memory.

### 3. What happens when the container finishes execution?
When the container is done running, it stops automatically. It doesn’t disappear—it just stays there in a stopped state. You can check it or delete it if you don’t need it anymore.