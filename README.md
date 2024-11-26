# Basic node.js Docker example

*based on*
- *https://medium.com/@saranyasasikumar06/setting-up-docker-on-a-basic-node-js-server-a-step-by-step-guide-49969e4dd42a*
- *https://medium.com/@dhwajgupta27/build-a-node-js-server-in-5-minutes-quick-and-easy-server-setup-6eb594e8b26*


## Starting the Docker Container
1. `docker build -t node-docker-app .`
2. `run -p 3000:3000 -d --name node-docker-app node-docker-app`
3. `docker logs node-docker-app`


## Stopping the Docker Container
To stop and remove the Docker container, use the following commands:
```sh
docker stop node-docker-app
docker rm node-docker-app
```


