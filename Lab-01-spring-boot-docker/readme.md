For building the docker image:
sh bin/package-and-build.sh
OR
sudo sh bin/package-and-build.sh

For running the docker image:
docker run -d -p 8080:8080 -it spring-hello-world-api:0.1

For accessing the application on web browser:
http://localhost:8080/hello-world