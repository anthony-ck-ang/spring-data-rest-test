# spring-data-rest-mongodb-with-test

Project: Accessing MongoDB with Spring Data rest + Integration Test

- MongoDB is a NoSQL document database.
- stores data in flexible, JSON-like documents

- Integration Test is a software development process 
- where program units are combined and tested as groups in multiple ways.
- can expose problems with the interfaces among program components.

# Note
- Please check pom.xml for a list of dependencies used.
- Please use a restful client or curl -i on command line to test this application.

# MongoDB installation & startup
1. Open a command line & cd into your project directory
2. On the command line type
  - brew install mongodb
3. After install , launch the mongo daemon(background process)
  - mongod
  all output going to: /usr/local/var/log/mongodb/mongo.log
4. Start the MongoDB client from another terminal window by typing 
  - mongo
