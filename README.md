# Project Reflection and Learning Journey (by seanpzk)

## Description:
Exploring Docker fundamentals through hands-on learning

## Concepts learnt:
- Relationship and mechanism of images and containers
- Utilising port binding to properly access containers
- Storage of images in repositories (public and private)
- Using docker compose to define and manage multi-container Docker applications
- Common CLI docker commands to run docker 

## Application:
I applied the Docker knowledge gained from this tutorial to another project, specifically [NUS Orbital](https://github.com/seanpzk/csDuck/commits/docker). By incorporating Docker into the project, I was able to run multiple containers that host the (static) servers, enabling efficient scalability. Additionally, the use of Docker made it simple for anyone with the image to host my static website, and I significantly reduced image size through the use of multi-stage builds. While these achievements were substantial, there is room for further improvement, particularly in hosting the dynamic website and containerizing the MongoDB database, which I would visit again after learning other DevOps tools!

## Acknowledgments:
Thank you [TechWorld with Nana](https://www.youtube.com/@TechWorldwithNana) for the free course!


# README content from the original project below!
This is an accompaying demo project for a "Docker in 1 hour" crash course on YouTube: https://www.youtube.com/@TechWorldwithNana
