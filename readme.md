# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- To install and run the machine on this repo, make sure to clone this repo into a directory on your local machine. From there, make sure you have installed Docker.

- You can verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`

- Then, run `docker-compose up` from the **project root directory** to load Anythink's backend and frontend.If Docker is working correctly, the backend should be running and able to connect to your local database.

- You can test that the backend is connected to the local database (posgres) via pointint to the browser url: `http://localhost:3000/api/ping`

- You can check that the backend is connected to the frontend by creating a new user via `http://localhost:3001/register`
