# Nest + Docker

Project cloned from (NestJS Typescript Starter)[https://github.com/nestjs/typescript-starter.git]

## Installation

```bash
$ npm install
```

## Running the app

```bash
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

## Docker

Container based on (How to write a NestJS Dockerfile optimized for production)[https://www.tomray.dev/nestjs-docker-production]

I decided to added tini like a challenge for my studies

```bash
docker image build -t app-nest .

# run
docker run --name app-nest -p 3000:3000 -it app-nest

```
