Following NestJS course https://www.udemy.com/course/nestjs-zero-to-hero/

This project use NestJS, Mongo and GraphQL

## Installation

```bash
$ npm install
```

## Running the app

```bash
# start mongodb docker image
$ docker run --name mongo -p 27017:27017 -d mongo

# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
