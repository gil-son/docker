# docker - concepts - Dockerfile.md

## Dockerfile

<ul>
  <li>
      The image has the application
  </li>
  <li>
      Dockerfile has instructions of what to do inside the image
  </li>
  <li>
      docker build will look for the Dockerfile
  </li>
</ul> 
  

## Some commands


<ul>
  <li>
      FROM: specifies an image to serve as a base, usually an OS with the application
  </li>
  <li>
      COPY: copies a file in the same directory and directs where to set
  </li>
  <li>
      ADD: copy in the same directory/downaload url a file and direct to where to set unpack the file
  </li>
  <li>
      RUN: run some command in the container, could be an app in one location, update, etc.
  </li>
  <li>
      CMD: execute a command when the container is initialized. It is an after-run process. It accepts an array
  </li>
  <li>
      ENV: creates an environment variable
  </li>
  <li>
      COPY: copy the file to a location
  </li>
  <li>
      EXPOSE: Expose a door inside the container when it starts. So it is possible to access the door, being outside the container
  </li>
</ul> 

## Examples commands in the Dockerfile

```
FROM  openjdk
COPY aula.txt /app/aula.txt
ADD aula.tar.gz /app/aula
RUN apt-get update && apt-get install
CMD ["/app"]
ENTRYPOINT ["ls"]
WORKDIR /app
ENV MINHA_APLICACO=app.jar
COPY $MINHA_APLICACAO /app
EXPOSE 8080
```












  

