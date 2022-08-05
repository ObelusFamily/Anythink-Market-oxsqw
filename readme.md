# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To setup this repo you first need to install docker in your system. 

Download docker for your respective os from here https://docs.docker.com/get-docker/

To check the docker is running fine use docker -v command in terminal. 

Then run "docker-compose up" from the project root directory to load Anythink's backend and frontend.

Test that everything is done correctly by visiting these two url  http://localhost:3000/api/ping, http://localhost:3001/register.
