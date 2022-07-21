## Description

NestJS course from Udemy.

## Installation

```bash
$ yarn
```

## Running the app

```bash
# development
Create database mediumclone, user mediumclone, password 123 in postgres (see ./src/ormconfig.ts)

$ npm run db:create
$ npm run db:migrate
$ npm run db:seed

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
