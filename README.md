# Federated-Learning

## Run the following commands in the terminal, make sure that docker is installed...
  - mkdir fl
  - cd fl
  - git clone https://github.com/Ahmed-Dirir/Federated-Learning.git
  - cd Federated-Learning
  - cd server
  - docker build -t server .
  - cd ..
  - cd client
  - docker build -t client .

## Run this command to start the server, it will be listening on port 5000 on the local host..
  - docker run --rm --network host server

## Run this command to start a client, you can run many times, a client will.
  - docker run --rm --network host client

