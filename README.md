# spring-data-rest-mongodb-with-test

Project: Accessing MongoDB with Spring Data rest + Integration Test

# MongoDB installation & startup

MongoDB is a NoSQL document database.
Stores data in flexible, JSON-like documents.

1. Open a command line & cd into your project directory
2. On the command line type   "brew install mongodb"
3. After install , launch the mongo daemon(background process)
   "mongod
  all output going to: /usr/local/var/log/mongodb/mongo.log"
4. Start the MongoDB client from another terminal window by typing 
   "mongo"


# Integration Test 
A software development process,
where program units are combined and tested as groups in multiple ways.
Can expose problems with the interfaces among program components.

# Note
- Please check pom.xml for a list of dependencies used.
- Please use a restful client or curl on command line to test this application manually.

- Please refer to ApplicationTests class in src/test/java and run as JUnit test to view the integration test.
- Code review of ApplicationTests class is done for basic understanding of integration test.
- Please hover over the respective .attributes/ .methods and refer to the inline comments for basic understanding.

