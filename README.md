# Content Video 1
Dockerize the NestJS starter App.  
https://www.youtube.com/watch?v=BrlQthcUHGw

# Content Video 2
- Add a docker-compose file and run also a postgres db
- Connect with NestJS to the db
- Post Data && Get Data over http (to NestJS) and then save it in the db

# You need
- NPM
- Node.js
- NestJS
- Docker


# Start Commands for Docker
Build your image:  
`docker build <your path> -t <<user>/project-name>`  

Run:  
`docker run -p 8080:3000 <<user>/project-name>`  

For Example:  
`docker build <your path> -t thomas-oliver/nestjs-dockerized`  
`docker run -p 8080:3000 thomas-oliver/nestjs-dockerized`  

Basic Docker Commands:  
List your docker images: `docker images`  
List your running containers: `docker ps`  
Kill a running container: `docker kill <id of container from docker ps (first 3 letters)>`, eg `docker kill fea`  





