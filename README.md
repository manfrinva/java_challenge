JAVA CHALLENGE
Manual deployment
Requirements
It's application requires the following: Java 8, maven and git;

Generates jar File
It's necessary to package the code:

mvn install
mvn package
Run application

Run unit test
mvn test

Run Integration tests
mvn clean test-compile failsafe:integration-test
