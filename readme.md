# Application dockerization
## DevOps and CI Kyiv-Mohyla Academy course

**In order to run this app in Docker container, please follow next steps:**

1. Clone this repository
2. Run command `docker build . -t  registry.gitlab.com/gribochechek/node_app_dockerized` for building docker image
3. Run command `docker run --memory=512m --cpus="1" -p 80:3000 -d --rm  registry.gitlab.com/gribochechek/node_app_dockerized` to run container

Docker registry link
https://gitlab.com/gribochechek/node_app_dockerized/container_registry




