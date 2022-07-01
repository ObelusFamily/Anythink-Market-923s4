# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup:
1. Install Docker and Docker-compser on your desktop
2. Navigate to project root directory and run "docker-composer up" command.
3. It will take some time to download dependencies and get both backend and frontend started.
4. To test the backend - try http://localhost:3000/api/ping in your browser.
5. To test the frontend and it's connectivity with backend - try http://localhost:3001/register and then try registering with some creds.
