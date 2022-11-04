# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Clone the repo in your local machine.

```bash
  git Clone https://github.com/ObelusFamily/Anythink-Market-lrq7wx91.git
```


Go to the root directory and run docker-compose up 

```bash
  docker-compose up
```
to install all the dependencies for the project.

Navigate to 
```bash
  http://localhost:3001
```
to see the application.
