# webserver-with-nginx

Instructions to run:
1. Download the files into a directory
2. Open cmd line and navigate to the directory
3. Create an image using `docker build -t reverseproxy .`. Note the '.' character at the end to specify to docker to look within the current directory for Dockerfile.
4. Using `docker images`, you should be able to see the image created. We need this image as the docker-compose.yml expects this image.
5. Run `docker-compose up -d` 
6. Navigate to localhost:8080 and then localhost:8081 and we should be able to see our 2 servers.
