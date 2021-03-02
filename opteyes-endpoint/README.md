# opteyes-endpiont

## gitlab 

variables used by the mysql database service specified in services

cache had to be added in order for yarn and npm builds to populate the node_modules/.bin folder, which is used in scripts like sequelize

an attempt at using docker-compose to run tests led to the issue of never-ending steps (as the db continues to run infinitely

)