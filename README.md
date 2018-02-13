###Applying Changes Using Command Line Liquibase

The easiest way to execute liquibase from the command line is to use Maven. Here are some useful commands:

* `mvn package` - build the package for the first time
* `mvn liquibase:status` - Show the status of the database
* `mvn liquibase:update` - Ensure the database is up to date
* `mvn liquibase:rollback -Dliquibase.rollbackCount=1` - Rollback the last change
