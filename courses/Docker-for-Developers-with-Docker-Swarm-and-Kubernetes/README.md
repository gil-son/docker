# docker

## Docker docs - courses - Docker-for-Developers-with-Docker-Swarm-and-Kubernetes

### What is Docker?

<ul>
   <li>Docker is software that reduces the complexity of application setup/commands</li>
    <li>Where we configure containers, which are like servers to run our applications</li>
   <li>Easily, we can create independent environments that work on different OS`s</li>
   <li>And it still leaves performance projects</li>
</ul>

 

### Why Docker?

<ul>
    <li>Docker provides more speed in setting up a dev environment</li>
     <li>Little time spent on maintenance, containers run as configured</li>
    <li>Performance to run application, better than a VM</li>
    <li>Rescue us from the Matrix from Hell</li>
</ul>
   

### The Matrix From Hell

<p>
    Imagine a company that has computers to install various software. This would require a lot
    time. Imagine that this company has grown and now it needs these facilities resources to be also
    installed on other devices such as servers and/or in the cloud. This scenario illustrates what The Matrix From Hell is.
</p>
   
<p>
    The Docker being universal manages to meet these devices with the necessary installations.
</p>
   

   
### Difference of Docker Versions

<ul>
   <li>Docker is divide in two versions: CE x EE</li>
    <li>CE is Community Edition, free edition, that possibility use Docker and is use in this course</li>
   <li>EE is Enterprise Edition, pay edition, there are more assurance of version that are lanched and support from Docker team</li>
</ul>


### Testing Docker

<ul>
    <li>Testing Docker with a real image</li>
    <li>To execute containers use the command docker run</li>
    <li>In this command is possible use many parameters</li>
    <li>In this example just pass the name of image that is docker/whalesay</li>
    <li>A command named cowsay and a message</li>
</ul>

```
docker run docker/whalesay cowsay Hello_World
```
<p>
    This command will check if it exists locally that image, if not the command wiill pull the image from the Docker repository, download it in parts and leave it in cache memory.
    With this the image will be saved in cache and when you do the command again, the same process will not be necessary, because now exist locally and it will occur faster
</p>

<hr>


### Source

<ul>
  <li>
     <a href="https://ibm-learning.udemy.com/course/docker-para-desenvolvedores-com-docker-swarm-e-kubernetes/learn/lecture/25063634#overview">
     Udemy Docker para Desenvolvedores (com Docker Swarm e Kurbernetes)</a>
  </li>
</ul>
