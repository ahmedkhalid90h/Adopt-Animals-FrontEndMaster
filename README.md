# ac-react-adoption
Don't buy, adopt!

Pet Adoption is a small application built with [React.js](https://github.com/zeit/next.js), [React Hooks]

## Running Locally

1. Clone this repo
2. Type `cd react` to enter the project folder
3. Run `npm install` or `yarn install` and install dependencies
4. Rename `next.config-dev.js` to `next.config.js`
5. To use the Google Maps for the shelter details (also in pet details page), you must get an API key which you can then add to your mobile app, website, or web server.  Follow [this link](https://developers.google.com/maps/documentation/javascript/get-api-key) to get a Google Map API Key
6. Insert your API Key into the `next.config.js`
7. Run `npm run dev` or `yarn dev` and visit [localhost:3000](http://localhost:3000)

## Build

1. Run `npm i`
2. Run `npm run dev` or `yarn build`

## Live Example

You can test on http://localhost:5173/

## Note
You may experience some delays when you try to use search function due to Petfinder's very slow API responses.