Skeleton App for quick development start.

Already configured with Symfony 5.3 and Bootstrap5.

Clone this repository, run `docker-compose up -d` and start coding.

cd app/
run: `composer install` to install dependencies
run: `yarn install --ignore-engines` (there's the following error if you don't add --ignore-engines):
error @symfony/webpack-encore@1.5.0: The engine "node" is incompatible with this module. Expected version "^10.19.0 || ^12.0.0 || >=14.0.0". Got "10.16.0"

How to add **SCSS**:
`yarn encore dev --watch`

How to add **JS**:
`yarn encore dev --watch`
