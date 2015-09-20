# IntegrationTestExample
Example for integration tests that test a restful service

This Repository contains:

...a small RESTful service in Java that gives access to a user database (e.g., username, first name, last name, email), backed by a SQL database. 

The service supports the following calls:
- POST /api/v1/users -- creates a new user
- GET /api/v1/users -- lists all users
- GET /api/v1/users/user1 -- list information about user1
- DELETE /api/v1/users/user1 -- deletes user 1
- PUT /api/v1/users/user1 -- updates the information of user1
 

...integration tests, that test the folowing  

- (1) tests to cover all functionality you implemented.
- (2) tests that allows to check for performance regressions. They measure either response time and throughput. As a bonus, they highlight a missing SQL table index.


Tipps how to deploy a RESTful service and the tests in a continuous integration environment:
- TBD
 
 
