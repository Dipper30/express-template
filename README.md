# node-service-template

Node Service Template: Node.js + Typescript + Sequelize + Mysql

# Get Started

## Prerequisite

```shell
node > v20.5
```

## Install NPM

```shell
npm install
```

## Build Env File

Create file '.env.development'.
Paste and modify codes below.

```shell
# config
PORT = 3030
DOMAIN = 'localhost:3030'

# keys
TOKEN_PRIVATE_KEY = youwillneverknow
TOKEN_PUBLIC_KEY = youwillneverknow
TOKEN_EXPIRE_IN = 3000000
MD5_PRIVATE_KEY = youwillneverknow

# db
USERNAME = xxxxxx
PASSWORD = xxxxxx
DATABASE = demo
HOST = 127.0.0.1
DIALECT = mysql
DIALECT_OPTION = {'socketPath': '/tmp/mysql.sock'} #optional
```

## Init Mysql Database

Run Sql in files @/src/db/sql

## Run Project

```shell
npm run dev
```