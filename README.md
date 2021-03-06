# Amorphic

## Purpose

Front to back isomorphic framework for developing applications with node.js and mongoDB

## Installation

To get started with a more complex app see the [Amorphic Ticket Demo](https://github.com/selsamman/amorphic-ticket-demo/)

To start with a hello world follow these instructions

    $ npm install amorphic
    $ npm install Q

Then move these from `node_modules\amorphic` into the root

* `apps/` folder which contains a hello world app and a doctor patient app

* `config.json`

Create an `app.js` as follows:

    require('amorphic').listen(__dirname);

Start node.js

    $ node app.js --port <available port>

Bring up the hello world test page in your browser and add some worlds!

See this [blog post](http://elsamman.com/?p=117) for more info on Amorphic and this
[video ](http://www.screencast.com/t/Z5Y2jMTmJ) that demos the drpatient sample

## Testing

In order to run the tests for this repo, you will need to have the [Mocha](https://mochajs.org/) test framework installed.

    $ npm install -g mocha

Run all the tests:

    $ npm test

Run specific test (in this case, config test):

    $ npm run test:config

## Status

Amorphic is still under development.  The next major step is creating documentation and tests.  In the mean
time the amorphic-ticket-demo is the best resource

## License

Amorphic is licensed under the MIT license



