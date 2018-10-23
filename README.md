# DockerExample1
My first attempt in combination of using GitHub with Docker for Dummies

The code is actually the code from Docker Getting Started (https://docs.docker.com/get-started/part2/#build-the-app).

-Start Docker if not running yet.

-Build a container image out of the demofiles (in dir of Dockerfile and other sources): docker build -t case-a-container .

-Run the container: docker run -p 4000:80 case-a-container 

-go to localhost:4000 on your system in browser to see the app.

Still to learn:
-how to get rid of all containers (?) lingering around? (docker login;docker container ls -a shows many un-named containers)




