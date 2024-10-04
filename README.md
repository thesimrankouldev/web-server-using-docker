# web-server-using-docker
Containerizing a nginx web server using Docker.

Pre-requisites
1. Linux machine ( I am using AWS EC2 )
2. Ensure that Docker is installed in your machine. 

Steps:
1. Create a basic index.html. This is the file the server will serve.
2. Create a dockerfile to run a tomcat container on the EC2 which will serve the index.html.
3. Build the docker images & run it.
4. Access the website using localhost:port. 
