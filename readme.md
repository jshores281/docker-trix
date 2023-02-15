# Docker-Trix: 
## A curated quick reference guide for creating dockerfiles and userful Docker commands.  
<br>

---
# SECTIONS
## 1. [Dockerfiles](#1-Dockerfiles)
## 2. [Docker Commands](#2-Docker-Commands)

---

<br><br>
# 1. Dockerfiles





<br></br>
# 2. Docker Commands

<br>


Builds docker image from dockerfile in current directory
<pre>
docker build -t [NEW/DOCKER-IMAGE-NAME] [./PATH/TO/DOCKERFILE]
</pre>


<br>

Creates and runs a new container from a selected docker image
<pre>
docker run -ditp [localhost-port:container-PORT] --name [Containers-name-UNIQUE] [Image-used]
</pre>


<br>


Enters CLI of Docker Container 
<pre>
docker exec -it [CONTAINER ID] bash
</pre>



<br>



Shows running docker containers
<pre>
docker ps -a
</pre>


<br>


Shows only running docker containers ID's
<pre>
docker ps -a -q
</pre>


<br>


Shows docker images pulled from docker hub in registery
<pre>
docker image ls
</pre>


<br>

Starts one Docker container in CLI mode
<pre>
docker start -ia [CONTAINER ID]
</pre>

<br>


Starts many docker containers at once
<pre>
docker start [CONTAINER ID...CONTAINER ID]
</pre>


<br>

Stops one or many docker containers
<pre>
docker stop -t 0 [CONTAINER ID...CONTAINER ID]
</pre>


<br>

Exits(closes) a Docker Container
<pre>
docker kill [CONTAINER ID...CONTAINER ID]
</pre>


<br>

Deletes one or many docker containers
<pre>
docker rm [CONTAINER ID...CONTAINER ID]
</pre>




