### Docker Instructions
- To build Dockerfile, run:
`docker build -t discovery-service:latest .`

- To run Docker container as a daemon, run:
`docker run -d --net=container:config-service --name discovery-service $IMAGE_ID`
