# NodeGinX Heroku Server
Experimental deployment test for Reverse Proxy Nginx + Node Server running on Heroku


#Requirements

**Write & test any scripts required to deploy a reverse proxy nginx server (v:1.10.1.7)**

**Write scripts to deploy a NodeJS server with optional child processes that scale based on CPU cores**

**Load necessary ENV vars based on Server resources, Node settings, and Nginx settings**

**Create needed mnaully configured ENV vars in Heroku admin panel**

**Configure or find necessary Buildpacks**

**Create Procfile to launch all needed services/processes**

**Configure SSL certificate with Nginx & find how to bundle SSL in deployment**

**Setup autobuild, CI, and hooks to Heroku server**
|

|

**Create test environment in NodeJS (v:6.x) to confirm:**

--> MongoDB connection & proper conn string data set as ENV var

--> S3/static file store URI redirecting (test using secondary web server instead of S3)

--> Setup npm requirements

