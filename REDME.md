# Run app with docker
    1: docker build -t portfolio:latest .
    2: docker ps -a
    3: docker image ls
    4: docker run --name portfolio -p 8080:80 -d portfolio:latest
