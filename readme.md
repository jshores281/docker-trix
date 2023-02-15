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



<pre>
docker build -t ubuntu-image1 .
</pre>


Creates and runs a new container from a selected docker image
<pre>
docker run -ditp [localhost-port:container-PORT] --name [Containers-name-UNIQUE] [Image-used]
</pre>




Shows running docker containers
<pre>
docker ps -a
</pre>


Shows docker images pulled from docker hub in registery
<pre>
docker image ls
</pre>


Starts one or many docker containers 
<pre>
docker start -ia [CONTAINER ID...CONTAINER ID]
</pre>


Stops one or many docker containers
<pre>
docker stop -t 0 [CONTAINER ID...CONTAINER ID]
</pre>



<pre>
docker kill [CONTAINER ID...CONTAINER ID]
</pre>



<pre>
docker rm [CONTAINER ID...CONTAINER ID]
</pre>




