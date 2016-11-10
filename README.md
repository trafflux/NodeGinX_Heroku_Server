# NodeGinX Docker Demo App
Experimental deployment test for Reverse Proxy Nginx + Node Server running on Docker

#Docker 

https://hub.docker.com/_/node/

Image based on `6.9.1-slim` Nodejs version

BUILD: `$ docker build -t node-dock-bld:0.9.4 . `

RUN: `$ docker run -it --rm --name nodedockbld node-dock-bld:0.9.4 `

NOTE: For quick and dirty creation of container from new Node ver, use `FROM: node:7-onbuild `


#Requirements

**Write & test any scripts required to deploy a reverse proxy nginx server (v:1.10.1.7)**

**Write scripts to deploy a NodeJS server with optional child processes that scale based on CPU cores**

**Load necessary ENV vars based on Server resources, Node settings, and Nginx settings**

**Create needed manually configured ENV vars in a config js file or bash script with prompts**

**Create script to launch all needed containers (nginx & node & mongo[?])**

**Configure SSL certificate with Nginx & bundle SSL in deployment**

|

|

**Create test environment in NodeJS (v:6.9) to confirm:**

--> MongoDB connection & proper conn string data set as ENV var

--> S3/static file store URI redirecting (test using secondary web server instead of S3)

--> Setup npm requirements

