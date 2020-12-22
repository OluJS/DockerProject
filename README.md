# DockerProject

## What is Docker?

Docker is a containerization platform that packages applications along with its binaries & libraries in the form of docker containers to allow the applications to work seemlessly in various environments. Containers sit on top of the hardware, sharing the same operating system (OS) between each one in existence. Inbetween the OS and the containerized applications sits the container engine. The purpose of the container engine is to expose parts of the shared OS into the partitions.

## Why I'm using Docker

Being that Docker shares the same OS between the different containers, the amount of diskspace used is significantly smaller compared to using a virtual machine (VM). Start up times are reduced, performances are more efficient and greater portability as most systems are compatible with Docker. A disadvantage however, is that if the shared OS corrupts, it'll affect all the containers. On the other hand, it should be quick to bring them back up again.

Cross browser testing can be carried out simply by creating specific nodes configured to different browsers. Using TestNG, I can run each test in parallel across those configured nodes instead of sequentially.
