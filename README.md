# E-commerce Back End

## Description

This repository is an e-commerce back end application for managers in an internet retail company that uses latest technologies in order to compete with other companies.

## Installation

Run `npm i`

Change `.env.example` to `.env` and put mysql information in

Within db folder:
* Run `mysql -u root -p`
* When in mysql `source schema.sql`
* Exit msql

Seed database in main folder by command-line command:
`node seeds/index.js`

Initialize application: `node server.js`

## Walkthrough Video

[E-commerce Back End](https://drive.google.com/file/d/1V6OEXeORqvdCIYYLMMMjdACDb5DTcRhw/view)


## Change Log

### 2022-09-21
* Updated README
* Fixed product.create

### 2022-09-14
* Fixed associations, finished route paths for the other routes
* Built all routes for category-routes.js
* Finished creating associations between models
