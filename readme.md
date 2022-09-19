# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. Clone the Repository.
2. Install [Docker](https://docs.docker.com/get-docker/ "Get Docker")
3. Go the project root directory.
4. Run the below command to load Anythink's backend and frontend.  
    Linux(WSL)
```bash
sudo docker compose up
```
5. Go to the browser and search http://localhost:3000/api/ping to check is backend is running.
6. Search for http://localhost:3001/register to check the frontend.

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
