# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone repo
2. Make sure that you've got `Docker` installed. If not, install it first.
3. Run `docker -v` and `docker-compose -v` to make sure that Docker has been installed successfuly
4. Go to root directory of a project and run `docker-compose up`
5. Check if backend is working by visiting http://localhost:3000/api/ping
6. Check if frontend is working by visiting http://localhost:3001
