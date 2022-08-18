# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To start using the repo, Docker needs to be installed. 

If you don't have it on your machine, you can download it from the (Docker website)[https://docs.docker.com/get-docker/].

To check that the installation of the required files was succsessful, you can run `docker -v` and `docker-compose -v`. It will yeld the installed version if all went well.

After this, you can run on your terminal `docker-compose up` and, on your browser, go to (http://localhost:3000/api/ping)[http://localhost:3000/api/ping] to check that the backend is up and running.

If everything works properly, you can go to (https://localhost:3001/register)[https://localhost:3001/register] and create a new user.

That's it, the environment is ready, well done!
