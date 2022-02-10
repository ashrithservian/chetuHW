For building the image:
docker build -t apache-static-web-page:0.1 .

For running the image:
docker run -d -p 80:80 apache-static-web-page:0.1

For accesing the image:
http://localhost/