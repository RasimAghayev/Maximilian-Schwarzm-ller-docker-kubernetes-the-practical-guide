---
title: "Maximilian Schwarzmüller - Docker & Kubernetes: The Practical Guide [2022 Edition]"
author: "Rasim Aghayev"
---

# Maximilian Schwarzmüller-docker-kubernetes-the-practical-guide

Tutor url : [Maximilian Schwarzmüller - Docker & Kubernetes: The Practical Guide [2022 Edition]](https://www.udemy.com/course/docker-kubernetes-the-practical-guide/)

# Sections
<details>
   <summary> 1: Getting Started</summary>
<p>
   
<details>
   <summary> - 2. What Is Docker?</summary>
<p>

Docker is a container technologyI A tool for createing and managing containers.

>#### Container 
>   - A standardized unit of software
>   - A package of code and dependencies to run that code (e.g. NodeJS code + the NodeJS runtime).
>   - The same container always yields **exact same application and execution behavior!** . No matter where or by whom it might be executed.
>   - Support for Containers **is built into** modern operating systems.
>   - **Docker simplifies** the creation and management of such containers.

</p>
</details>

<details>
   <summary> 
		- 3. Why Docker & Containers?
   </summary>
<p>

> - #### We Want Reliability & Reproducible Environments
>   - We want to have the **exact same environment for development and production=>** This ensures that it works exactly as tested
>   - It should be easy to **share a common development environment** / setup with (new) employees and colleagues.
>   - We **don't want to uninstall and re-install**  local dependencies and runtimes all the time
> - #### Why Containers?
>   - Why would we want **independent, standardized " application packages"** ?
>     - Different Development & Production Environments => We want to build and test in exactly (!) the same environment as we later run our app in.
>     - Different Development Environments Within a Team / Company => Every team member should have the exactly (!) same environment when working on the same project.
>     - Clashing Tools / Versions Between Different Projects => When switching between projects, tools used in project A should not clash with tools used in project B
> - #### A Containers?
>   - **Standardized** unit for shipping goods
>   - Can be **moved** with trucks, ships, cranes, ...
>   - **Independent** from other containers
>   - **Self-containing**
	
</p>
</details>
 
 
<details>
   <summary> 
		- 5. Virtual Machines vs Docker Containers
   </summary>
<p>

> - Virtual Machines / Virtual OS: Summary
>   - Pro
>     - Separated envionments
>     - Environment-specific configurations are possible
>     - Environment configurations can be shared and reproduced reliably
>   - Con
>     - Redundant duplication, waste of space
>     - Performance can be slow, boot times can be long
>     - Reproducing on another computer/server is possible but may still be tricky
> - Containers vs Virtual Machines
>   - Docker Containers
>     - Low impact on OS, very fast, minimal disk space usage
>     - Sharing, re-building and distribution is easy
>     - Encapsulate apps/environments instead of "whole machines"
>   - Virtual Machines
>     - Bigger impact on OS, slower, higher disk space usage
>     - Sharing, re-building and distribution can be challenging
>     - Encapsulate "whole machines" instead of just apps/environments
	
</p>

</details>

<details>
   <summary> 
		- 6. Docker Setup
   </summary>
<p>

> - [Linux](https://docs.docker.com/engine/install/)
> - [MacOS](https://docs.docker.com/desktop/install/mac-install/) ( [Old version](https://github.com/docker-archive/toolbox/blob/master/docs/toolbox_install_mac.md) )
> - [Windows](https://docs.docker.com/desktop/install/windows-install/) ( [Old version](https://github.com/docker-archive/toolbox/blob/master/docs/toolbox_install_windows.md) )
> - Docker Playground
>   - If you can't install Docker on your system, you can also look into this online playground: [https://labs.play-with-docker.com/](https://labs.play-with-docker.com/). For the most part, you should be able to follow along without issues with this playground.
	
</p>
</details>

<details>
   <summary> 
		- 11. An Overview of the Docker Tools
   </summary>
<p>

> - Docker Engine
> - Docker Deskop (incl. Daemon & CLI)
> - Docker Hub
> - Docker composer
> - Kubernetes

</p>
</details>

<details>
   <summary> 
		- 12. Installing & Configuring an IDE
   </summary>
<p>

> - [VSCode](https://code.visualstudio.com/docs/containers/overview)
> - [PHPStorm](https://plugins.jetbrains.com/plugin/8595-php-docker)
> - ....

</p>
</details>


<details>
   <summary> 
		- 14. Course Outline
   </summary>
<p>

#### Getting Started & Overview
> - Foundation
>   - Images & Containers
>   - Data & Volumes (in Containers)
>   - Containers & Networking
> - "Real Life"
>   - Multi-Container Projects
>   - Using Docker-Compose
>   - "Utility Containers"
>   - Deploying Docker Containers
> - Kubernetes
>   - Kubernetes Introduction & Basics
>   - Kubernetes: Data & Volumes
>   - Kubernetes: Networking
>   - Deploying a Kubernetes Cluster

</p>
</details>
</p>
</details>

--------------------------------------------------------------
<details>
   <summary>2: Docker Images & Containers: The Core Building Blocks</summary>
<p>
<details>
   <summary> 
		- 18. Images & Containers: What and Why?
   </summary>
<p>

>   - Docker
>      - Images
>         - Templates / Blueprints for containers
>         - Contains code + required tools/runtimes
>      - Containers
>         - The running "unit of software"
>         - Multiple containers can be created based on one image

</p>
</details>
<details>
   <summary> 
		- 19. Using & Running External (Pre-Built) Images
   </summary>
<p>

> We need an Image!	
>   - Use an **existing, pre-built Image**
>>      - e.g via Docker Hub
>>> ```Shell
>>> docker run node
>>> docker run -it node
>>> docker ps -a
>>> ```

>   - Create your **own, custom Image**
>>      - Write your own Dockerfile (based on another Image)
>>> ```Shell
>>> docker run node
>>> docker run -it node
>>> docker ps -a
>>> ```
</p>
</details>


	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	Template
<details>
   <summary> 
		- 18. Images & Containers: What and Why?
   </summary>
<p>

>   - Docker
>      - Images
>         - Templates / Blueprints for containers
>         - Contains code + required tools/runtimes
>      - Containers
>         - The running "unit of software"
>         - Multiple containers can be created based on one image

</p>
</details>


</p>
</details>


<details>
   <summary>CLICK ME</summary>
<p>

Code ...
</p>
</details>

