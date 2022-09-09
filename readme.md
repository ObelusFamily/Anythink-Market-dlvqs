# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1.Clone the git repository. Please notice: Do not fork it. Clone it.
2.Install Docker(https://docs.docker.com/get-docker/).
3.verify that docker is ready on your system by running "docker -v" or "docker-compose -v" in terminal.
4.Run "docker-compose up" from your system's project directory to load Anythink's backend and frontend.
5.Check the previous step by pointing your browser to (http://localhost:3000/api/ping).
6.If everything is working correctly, you will be able to create a new user on (http://localhost:3001/register).
7.Run all scripts on one of the containers created by "docker-compose up".
8.You can use "docker exec" to run commands on a running container.
