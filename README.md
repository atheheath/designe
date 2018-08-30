### Designe

## Design first real time templated deck creation

## Ubuntu Dependencies
* python
  * `sudo apt install python3.5.2`
* npm
  * `sudo apt install npm`
* node
  * `curl -sL https://deb.nodesource.com/setup_8.x && sudo apt install nodejs build-essential`

## Python Dependencies
Flask==1.0.2
Flask-Cors==3.0.4

## NPM Dependencies
npm install -g vue-cli@2.9.3
npm install axios@0.18.0 --save
npm install bootstrap@4.1.1 --save
npm install bootstrap-vue@2.0.0-rc.11 --save

## Starting up servers
To start up the frontend, run
```
cd client && npm run dev
```
To start up the backend, run
```
cd server && python add.py
```

## Resources
https://testdriven.io/developing-a-single-page-app-with-flask-and-vuejs
https://www.fullstackpython.com/flask.html

## Notes
Everything affecting the app is generally in `client/src`.

To route to new components, update `client/src/router/index.js`. 
This means creating a way to route a url to a component action.

`client/src/main.js` handles the generic importing and is the main entry point for the project.

When installing npm dependencies, make sure you're in the `client/` directory, otherwise stuff won't work.

In `.vue` files, the main sections are 
* `<template>`
  * Creates the template with how to deal with the data and render HTML
* `<script>`
  * Javascript interactions
* `<style>`
  * CSS stuff

`<template>` in `.vue` files utilizes data defined in `<script>` as a data structure.
