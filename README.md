# Docker Nginx
## For start

docker build -t first-docker .

docker run --name=runned-docker -p 8000:80 -d first-docker:latest

