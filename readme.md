# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1 - Clone repo to your machine

2 - Download Docker Desktop app - https://docs.docker.com/get-docker/

3 - After restarting, it will prompt you to install a Linux Kernal update and restart again

4 - Try running "docker -v" and "docker-compose -v" to verify installation

5 - Open Docker Desktop

6 - Open control panel and navigate to the root of the Anythink-Market-elerx project

7 - Run docker-compose up in the root directory

8 - Navigate to http://localhost:3000/api/ping to verify Docker is running properly
