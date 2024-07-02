# Dockerized Vulerable Web App Lab
## What it is
Simple docker-compose that stands up some of my favorite vulnerable web apps. Get to the apps by accessing
http://localhost   --- Damn Vulnerable Web Application  
http://localhost:81/WebGoat  --- WebGoat  
http://localhost:82 --- OWASP Juiceshop  
http://localhost:83 ---- phpldapadmin vulnerable container  
http://localhost:84 ---- vAmPI Vulnerable API service
http://localhost:85 ---- vAmPI Secured API  
**These actually listen on all interfaces. Please do not host this on a public facing server, if you do, someone is going to laugh at you. And possibly access your shit, just be safe <3** 

## What it isn't

Anything special. It is currently services that I use often that I was tired of standing up in a complicated way. This requires nothing more than `docker-compose up` to stand all the services up. 
## What's to come
Adding more vulnerable webapps as I find them. That is pretty much it. 
