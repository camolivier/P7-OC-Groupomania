# Groupomania | Openclassrooms P7

Fullstack implementation of an corporate social network

## Getting started

### 1- Pre requisites

- You will need to have Node and [npm] installed locally on your machine.
- Clone or download this repository

### 2- Backend installation

From the _backend_ directory:

- Remove the .sample extension from the .env file and fill the `DB_USERNAME` and `DB_PASSWORD` fields with your MySQL login infos.
- Run `npm install` command to install the backend dependencies.
- Run `npm run db-init` command to initialize the MySql database and populate it with mock data.
- Run `npm start` command to launch the API

At this point the server should be running on port 8080 and the following messages should be displayed in your terminal :

```bash
Listening on port 8080
...
connected to database...
```

### 3- Frontend installation

From the _frontend_ directory:

- Run `npm install` command to install the frontend dependencies.
- Run `npm start` to launch the frontend server in development mode.

At this point, the application should automatically start running in your web browser.

### 4- Demo accounts (admin)

If you would like to login as an administrator or a moderator, please use the demo accounts.  
Login details are given in the .env file in the _frontend_ directory.

## Project Overview

### Built with

Backend

- Node JS / Express
- MySQL / Sequelize

Frontend

- React
- Bootstrap / React Boostrap / Styled Components

