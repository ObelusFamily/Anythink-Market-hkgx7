# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Go ahead and download Docker and Docker Compose plugin from [Docker Site](https://docs.docker.com/get-docker/)

- Next Run `docker compose -v` and `docker -v` to verify the installation. 

- Now clone the official anything repo and from the project root directory run `docker compose up`

- And done, if everything went right you should be able to see a message on https://localhost:3000/api/ping

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
