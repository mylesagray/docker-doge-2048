# docker-doge-2048

A dockerised version of doge2048.

Based on [aferrera/2048](https://github.com/laferrera/doge2048.git)

## Run the docker container with your own build

    git clone https://github.com/mylesagray/docker-doge-2048.git
    git submodule update --init --recursive
    docker build -t "docker-2048" .
    docker run -d -p 8080:80 docker-2048

## Run the docker container by pulling the image directly

    docker run -d -p 8080:80 mylesagray/docker-2048

## Access the game

    http://127.0.0.1:8080
