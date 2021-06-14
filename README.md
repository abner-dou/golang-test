# golang-test

## Instructions
For this test, you should create the REST API service(s) in golang in order to perform CRUD operations for a "notes" platform.

### must contains the following operations:

- Create new `user`
- Get `user` list
- Get `user` by id
- Update `user` by id
- Delete `user` by  id
- Create a new `note` for `user`
- Get `note` list using `user id`
- Get `note` by `note id`
- Update `note` by id
- Delete `note` by id



### `user` must contain:
- name
- created at

### `notes` must contain: 

- description
- created at
- update at

## Database
The service(s) must store the information in a NoSQL database (can be `mongodb` or `cassandra`), for this is necessary to 
create a script to configure and run the DB from a docker image (you can choose it 
from docker hub)

## Unit testing
The project needs to have unit testing for the API, handlers, services, etc.

## Documentation
Is necessary to have the README.MD file with the instructions about how to run and how to test the project

## Code
The code must be hosted on github and be public

## Evaluation
We will evaluate: 
- golang coding
- api design
- testing
- docker usage
- clean code