# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
1) Download Docker and install
2) Verify Docker is running by typing the following commands into terminal "docker -v" and "docker-compose -v"
3) Find the root file of Anything-Market-zck28 and navigate there using terminal
4) Type in "docker-compose up"
5) Test by pointing browser to http://localhost:3000/api/ping
