# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Setting Up an Environment
Firstly clone the repository not fork it.
then create a github codespace and create a branch and commit changes
then create a codespace and run the following commands
```docker-compose up 
to load the front and backend

Once docker-compose finishes loading up, the backend should be running and able to connect to the database.
After the server is up, make sure you test it by pointing your browser to https://obelusfamily-anythink-market-5csve-q454xjv75p4f4jp7-3000.githubpreview.dev/api/ping
If everything is working properly, you’ll be able to create a new user on https://obelusfamily-anythink-market-5csve-q454xjv75p4f4jp7-3001.githubpreview.dev/register
and that's it, you're all set up.