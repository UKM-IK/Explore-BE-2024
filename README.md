<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

# Tech Stacks
- ProsgresSQL
- Postman
- Nest JS
- Typescript
- Swagger.io

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app
[Nest](https://docs.nestjs.com/) documentation.

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```


## Prisma
NestJS app with Express, [Prisma](https://www.prisma.io/docs) and nestjs-prisma.

```bash
# Adjust prisma/schema.prisma and perform a migration:
$ npx prisma migrate dev

# Seed the example database:
$ npx prisma db seed
```

# Exploring Project

**Brief :** <br />
As a Backend Developer you are required to create API a blog.

Please create API same as those contained in the API address https://gorest.co.in

## Task 1

_Feature to develop :_ **CRUD (Create Read Update Delete) Posts**

Endpoint :
https://gorest.co.in/public/v2/posts

Example Request for __POST/PUT/PATCH__:

```json
{
    "title": "ini judul blog",
    "body": "ini isi dari postingan blog"
},
```

Acceptance Criteria :

- User can view list of posts
- user can view detail of posts
- user can create new post
- user can update post
- user can delete post

## Task 2

_Feature to develop :_ **CRUD (Create Read Update Delete) Comments**

Endpoint :
https://gorest.co.in/public/v2/posts/{id_posts}/comments

Example Request for __POST/PUT/PATCH__
```json
{
    "name": "Cahyadi",
    "email": "cahyadi@utdi.ac.id",
    "body": "Postingannya keren sekali."
},
```

Acceptance Criteria :

- User can view list of comments in post page
- user can create new comment
- user can update comment
- user can delete comment

## Task 3

_Feature to develop :_ **CRUD (Create Read Update Delete) Users**

Endpoint :
https://gorest.co.in/public/v2/users

Example Request for __POST/PUT/PATCH__
```json
{
    "name": "Madoa",
    "email": "Madoa@utdi.ac.id",
    "gender": "male",
    "status": "active"
},
```

Acceptance Criteria :

- User can view list of users
- user can view detail of users
- user can create new users
- user can update users
- user can delete users

## Task 4

_Feature to develop :_ **CRUD (Create Read Update Delete) Todo Lists**

Endpoint :
https://gorest.co.in/public/v2/todos

Example Request for __POST/PUT/PATCH__
```json
{
    "title": "Makan Pagi",
    "due_on": "2024-02-17T00:00:00.000+05:30",
    "status": "pending"
},
```

Acceptance Criteria :

- User can view list of todo
- user can view detail of todo
- user can create new todo
- user can update todo
- user can delete todo