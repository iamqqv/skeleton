Skeleton App for quick development start with Symfony 5.3, Bootstrap5 and VueJS

Taken from https://www.twilio.com/blog/get-started-docker-symfony

Clone this repository, run `docker-compose up -d` and start coding.

## How to get up and running:

1. Clone this repository
2. Stop all running Docker Containers with ports 80 (Webserver) & 3306 (Database)
3. run `docker-compose up -d` (for detached mode) in your terminal
4. move into the app directory via `cd app/`
   1. run `composer install` or `composer update` to install dependencies
   2. run `yarn install` to install javascript dependencies
5. visit http://localhost:8080/

## Troubleshooting
If there's an error occuring like:

`error @symfony/webpack-encore@1.5.0: The engine "node" is incompatible with this module. Expected version "^10.19.0 || ^12.0.0 || >=14.0.0". Got "10.16.0"`

you should update your node version: https://nodejs.org/en/

How to add **SCSS**:
`yarn encore dev (--watch)`

How to add **JS**:
`yarn encore dev (--watch)`
