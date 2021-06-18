# game

simple is better

Base on nginx:alpine

# run the docker container with your own build

    git clone https://github.com/marizmendi/game.git
    docker build -t "game" .
    docker run -d -p 8080:80 game

# run the docker container by pulling the image directly

    docker run -d -p 8080:80 marizmendi/game

# Access the game

    http://127.0.0.1:8080

If you run docker with boot2docker on Mac or Windows, the URL should be:

    http://192.168.59.103:8080
