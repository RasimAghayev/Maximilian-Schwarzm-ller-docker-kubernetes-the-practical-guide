---
title: "Maximilian Schwarzmüller - Docker & Kubernetes: The Practical Guide [2022 Edition]"
author: "Rasim Aghayev"
---

# Maximilian Schwarzmüller-docker-kubernetes-the-practical-guide

Tutor url : [Maximilian Schwarzmüller - Docker & Kubernetes: The Practical Guide [2022 Edition]](https://www.udemy.com/course/docker-kubernetes-the-practical-guide/)


## 2. What Is Docker?

Docker is a container technologyI A tool for createing and managing containers.

#### Container 
   - A standardized unit of software
   - A package of code and dependencies to run that code (e.g. NodeJS code + the NodeJS runtime).
   - The same container always yields **exact same application and execution behavior!** . No matter where or by whom it might be executed.
   - Support for Containers **is built into** modern operating systems.
   - **Docker simplifies** the creation and management of such containers.

## 3. Why Docker & Containers?
  - ### We Want Reliability & Reproducible Environments
    - We want to have the **exact same environment for development and production=>** This ensures that it works exactly as tested
    - It should be easy to **share a common development environment** / setup with (new) employees and colleagues.
    - We **don't want to uninstall and re-install**  local dependencies and runtimes all the time
  - ### Why Containers?
    - Why would we want **independent, standardized " application packages"** ?
      - Different Development & Production Environments => We want to build and test in exactly (!) the same environment as we later run our app in.
      - Different Development Environments Within a Team / Company => Every team member should have the exactly (!) same environment when working on the same project.
      - Clashing Tools / Versions Between Different Projects => When switching between projects, tools used in project A should not clash with tools used in project B
  - ### A Containers?
    - **Standardized** unit for shipping goods
    - Can be **moved** with trucks, ships, cranes, ...
    - **Independent** from other containers
    - **Self-containing**

## 5. Virtual Machines vs Docker Containers
  - Virtual Machines / Virtual OS: Summary
    - Pro
      - Separated envionments
      - Environment-specific configurations are possible
      - Environment configurations can be shared and reproduced reliably
    - Con
      - Redundant duplication, waste of space
      - Performance can be slow, boot times can be long
      - Reproducing on another computer/server is possible but may still be tricky
   - Containers vs Virtual Machines
    - Docker Containers
     - Low impact on OS, very fast, minimal disk space usage
     - Sharing, re-building and distribution is easy
     - Encapsulate apps/environments instead of "whole machines"
    - Virtual Machines
     - Bigger impact on OS, slower, higher disk space usage
     - Sharing, re-building and distribution can be challenging
     - Encapsulate "whole machines" instead of just apps/environments

## 6. Docker Setup
   - [Linux](https://docs.docker.com/engine/install/)
   - [MacOS](https://docs.docker.com/desktop/install/mac-install/) ( [Old version](https://github.com/docker-archive/toolbox/blob/master/docs/toolbox_install_mac.md) )
   - [Windows](https://docs.docker.com/desktop/install/windows-install/) ( [Old version](https://github.com/docker-archive/toolbox/blob/master/docs/toolbox_install_windows.md) )
   - Docker Playground
     - If you can't install Docker on your system, you can also look into this online playground: [https://labs.play-with-docker.com/](https://labs.play-with-docker.com/). For the most part, you should be able to follow along without issues with this playground.
## 11. An Overview of the Docker Tools
   - Docker Engine
   - Docker Deskop (incl. Daemon & CLI)
   - Docker Hub
   - Docker composer
   - Kubernetes
## 12. Installing & Configuring an IDE
   - [VSCode](https://code.visualstudio.com/docs/containers/overview)
   - [PHPStorm](https://plugins.jetbrains.com/plugin/8595-php-docker)
   - ....
## 14. Course Outline
### Getting Started & Overview
 - Foundation
   - Images & Containers
   - Data & Volumes (in Containers)
   - Containers & Networking
 - "Real Life"
   - Multi-Container Projects
   - Using Docker-Compose
   - "Utility Containers"
   - Deploying Docker Containers
 - Kubernetes
   - Kubernetes Introduction & Basics
   - Kubernetes: Data & Volumes
   - Kubernetes: Networking
   - Deploying a Kubernetes Cluster
