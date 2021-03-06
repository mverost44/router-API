# Router.jn React Client

## About the app
router.jn is an app created out of necessity. The idea for this app stemmed from the lack of websites that can log road trips you've taken or plan to take. You can add places to travel to, expenses along the way, and add/delete todos that you plan on accomplishing in your travels.

## Installation
1. Start with Rails template from GA
2. Change api url in arc/auth/api.js to be dynamic based on deployment/development environments
3. Follow deployment recommendations

## Deployed apps and repositories
| Resource   | URL            |
|------------|----------------|
| client deployed    | https://jennasaurusrex.github.io/router-client/#/             |
| client app repo   | https://github.com/jennasaurusrex/router-client             |
| server deployed | https://router-jn.herokuapp.com/            |
| server api repo  | https://github.com/jennasaurusrex/router-API     |


## Technologies Used
- React.js
- React Router
- JavaScript
- Material UI
- Bootstrap
- Sass
- Webpack
- Node Package Manager
- Rails
- Ruby

## Route Catalog
| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/sign-up`             | `users#signup`    |
| POST   | `/sign-in`             | `users#signin`    |
| DELETE | `/sign-out`            | `users#signout`   |
| PATCH  | `/change-password`     | `users#changepw`  |
| GET    | `/trips`               | `trips#index`     |
| POST   | `/trips`               | `trips#create`    |
| GET    | `/trips/:id`           | `trips#show`      |
| PATCH  | `/trips/:id`           | `trips#update`    |
| POST   | `/trips/:id/todo/:id`               | `todo#create`    |
| DELETE   | `/trips/:id/todo/:id`  | `todo#destroy`   |
| POST   | `/trips/:id/expense/:id`               | `expense#create`    |
| DELETE   | `/trips/:id/expense/:id`  | `expense#destroy`   |

## Unsolved Problems
- Incorporate working google maps API into front end [COMPLETE]
- Incorporate AWS to upload photos taken [WIP]
- Fix tables in rails to CRUD on expenses. [COMPLETE]
- Add a photo table. 
- Add sharing with social media.

## ERD, Wireframes, and User Stories
[Link to gallery](https://imgur.com/a/Ht3TE7x)
