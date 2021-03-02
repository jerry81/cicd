# opteyes-endpiont

## gitlab 

variables used by the mysql database service specified in services

cache had to be added in order for yarn and npm builds to populate the node_modules/.bin folder, which is used in scripts like sequelize

an attempt at using docker-compose to run tests led to the issue of never-ending steps (as the db continues to run infinitely

## docker

the docker compose is used to run both db and datadog image for logging

## Jenkins

this example shows a freestyle project which runs a docker inside another docker a node image running the app linked to a mysql image