# A blazing fast REST APIs with Node.js, MYSQL, Fastify and Swagger.

> A Node.js project integrated with Sequelize

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm start
```
## Prerequisites
- Nodejs
- MYSQL

## What project can do
- Connect with Sequelize.
- Generate models, seeders and migrations. 
- Read seeders from file `csv`.
- Auto generate Controller, Routes files.
- Validation with `JOI`.
- Unit Test with `Mocha`
## Command line
- To generate model & migration:
```
node_modules/.bin/sequelize model:generate --name User --attributes firstName:string,lastName:string,email:string
```
- To generate seeders:
```
node_modules/.bin/sequelize seed:generate --name demo-user
```
- To generate controller & routes files:
```
npm run new
```
- To reset database: 
```
npm run migration:reset
```
