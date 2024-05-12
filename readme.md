## Basic Practice of NGINX using Docker

This project provides the most primitive practice of Web Serving using NGINX, which is appropriate for lesson of Web server infrastructure.

It requires Docker experience in advance because the server is constructed on a Docker container.

From the server, a simple HTML file written only "Success" is deliverd.

It is stored in /server/src and should be replaced with your build production when you would like to deliver more sophisticated application (probably requiring to edit /server/nginx/nginx.conf in addition).


## Procedure

1.
Install Docker on your PC. ()

2.
Open terminal in the directory that this README placed and execute the following command.

> docker-compose up --build

3.
Access the following URL from your favorite Browser.

> http://localhost:6300


## Using Tech. factor

Docker

NGINX

HTML