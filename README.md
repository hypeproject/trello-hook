## Prerequisites

* [Node.js](https://nodejs.org/en/download/current/)

* [Yarn](https://yarnpkg.com/) (alternative to NPM, not required)

  

## Installation

1. Install the dependencies with `yarn install` or `npm install`.

2. Copy the `.env.example` to `.env` and update the fields to reflect your environment
3. Creating webhook on https://developer.atlassian.com/cloud/trello/guides/rest-api/webhooks/
4. Creating Trello API Key, Secret, and Token https://trello.com/power-ups/
6. Callback url should end with /v1/trello

## How to get idModel
1. Go to your trello board
2. Add .json at end of url. example : (https://trello.com/b/123456/board.json)
3. Find idBoard
4. That is your idModel
  

## Usage

* To compile the TypeScript source to `.js` files, run `yarn build` or `npm run build`.

* To start the server, run `yarn start` or `npm start`.

* The project is now accessible [http://localhost:3000](http://localhost:3000).