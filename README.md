# QSql Tests

This project make use of Qt, docker and postgre in order to fetch and display all the users from a postgresql database, these users
has a relation with specific car present in another table, the use of QSql allows us to fetch data record using
relationship.

## Docker compose

The use of docker-compose in this case will help us build the PostgreSQL database among with its pgadmin4 which is used in order to initialize the database and also fetching the data without making use of the Qt application. This way We are able to test if the application is working or not.

### Docker compose with Qt

Actually the docker-compose isn't containing the Qt application, as a matter of fact the Qt application is actually not implemented, but the idea should be to run the compose, this way the database and the Qt application has to be ran at the same time.
