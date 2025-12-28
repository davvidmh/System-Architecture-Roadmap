\# System Architecture \& Engineering Roadmap Formal Documentation. Written by David Mendoza davvidmh@gmail.com UAM-I



This repository documents my progression from fundamental computer science concepts to designing high-performance distributed systems. 



Session 1. My Current Focus is: Mastering Containerization with Docker and Java Backend Architecture.



Roadmap Structure \[01-docker-java-basics]:

&nbsp; - Environment setup: JDK 21 \& Docker.

&nbsp; - Creation of Docker Images.

&nbsp; - "Write Once, Run Anywhere" implementation.



Tech Stack

\- Languages: Java 21, Python.

\- Infrastructure: Docker, AWS (Upcoming).

\- Tools: Git, Linux Shell.



Concepts learned this session:



Containerization vs. Virtualization: Understanding lightweight OS-level virtualization using the host kernel (WSL 2) to optimize resources, as opposed to heavy traditional Virtual Machines.



Immutable Infrastructure: The architectural principle where artifacts (Docker Images) are never modified after creation. Updates require building a new artifact, guaranteeing consistency across all environments.



Declarative Configuration: Using a Docker file to define the environment (insfraestructure) state explicitly in code, deprecating manual server configuration.



Build Context: Understanding how the CLI interfaces with the Docker Daemon to package source code and dependencies during the image build process.



Previous Concepts: Kernel, Virtualization, Conterinization, Daemon.

