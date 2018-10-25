# Simple NodeJS / MongoDB application

Posts are sorted in reverse chronological order and paginated.

## Configuration

Aspects of the app are controlled by the following environment variable. Feel free to modify them once deployed or before running locally.

| Name               | Description                                                                                          | Default                             |
| ------------------ | ---------------------------------------------------------------------------------------------------- | ----------------------------------- |
| PORT               | The port to run the webserver on                                                                     | 3000                                |
| PAGE_SIZE          | How many log items to display on each page in the application                                        | 10                                  |
| MONGODB_URI        | URI to connect to mongoDB instance. Usually automatically set using this variable on most providers. | mongodb://localhost:27017/hackerlog |
| HACKERLOG_PASSWORD | The password to post a log message                                                                   | P@ssw0rd!                           |

## Running locally

To run the app locally, simply run:
`yarn` to install the dependencies of the app and then `npm start` or `yarn start`

Note: You will need a working instance of MongoDB. You can install mongoDB community edition locally by following the tutorial for your platform at [this](https://docs.mongodb.com/manual/installation/#tutorials) link.
