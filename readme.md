# Application dockerization
## DevOps and CI Kyiv-Mohyla Academy course

**In order to run this app in Docker container, please follow next steps:**

1. Clone this repository
2. Run command `docker build . -t  registry.gitlab.com/gribochechek/node_app_dockerized` for building docker image
3. Run command `docker run --memory=512m --cpus="1" -p 80:3000 -d --rm  registry.gitlab.com/gribochechek/node_app_dockerized` to run container
4. Container will use port 80 to expose application

Docker registry link
https://gitlab.com/gribochechek/node_app_dockerized/container_registry


**In order to run this app locally, please follow next steps(you need to have Node.js and npm to be installed before running application):** 

1. Clone this repository
2. Run command `npm install`
3. Run command `node server.js`
4. App will be available on port 3000 by default. You can specify it in `server.js`