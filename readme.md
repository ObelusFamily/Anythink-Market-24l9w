# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.rst)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

```shell
  # Clone the repo locally:
  git clone git@github.com:ObelusFamily/Anythink-Market-24l9w.git Anythink-Market

  # Go into the project folder
  cd Anythink-Market

  # Run the docker compose command to bring up the database, backend and frontend:
  docker compose up -d

  # Test the backend:
  open http://localhost:3000/api/ping

  # Test the frontend:
  open http://localhost:3001/register  
```

