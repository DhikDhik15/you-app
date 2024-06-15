<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository. This repository consists of:

- 🔼 NestJS 10
- ✨ TypeScript
- 📏 ESLint — Find and fix problems in your code
- 💖 Prettier — Format your code consistently
- 🐶 Husky — Run scripts before they are committed
- 🔑 RBAC — Authentication and Role Authorization starter kit
- 📃 Pagination — Built-in pagination builder
- 📡 Socket.io — Websocket with authentication and realtime notifications
- ☁️ Chat — Implement a robust real-time chat feature using Socket.io, allowing seamless communication between users.
- 🔍 Cache — Redis
- 📄 Api Documentation — Swagger
- ⛵ Docker — Alpine, Redis, MongoDB
- 📕 Logger — Winston
- 🔚 End to End Testing — Perform end to end testing with different environment

## Installation

```bash
npm install
```

## Installation

```bash
npm husky install
chmod ug+x .husky/*
```

## Running the app

### development

```bash
npm run start
```

### watch mode

```bash
npm run start:dev
```

### production mode

```bash
npm run start:prod
```

## Running the app with Docker

## Seed role to MongoDB

```bash
npx nestjs-command seed:role
```

## File Storage

- Local (Set Storage to 'local' in .env)

## API Documentation

http://localhost:3000/swagger

## Simple Live Chat with WebSocket Demo

http://localhost:3000

## Test

### unit tests

```bash
yarn run test
```

### e2e tests

```bash
yarn run test:e2e
```

### test coverage

```bash
yarn run test:cov
```
