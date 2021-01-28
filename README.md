# gostack-api-nodejs

## Application routes

```
POST/repositories:
```
* The route must receive title, url and techs within the body of the request, the URL being the link to the github of this repository. 

```
GET/repositories:
```
* Route that lists all repositories;

```
PUT/repositories/:id
```
* The route should change only the title, url and techs of the repository that has the id equal to the id present in the route parameters;

```
DELETE/repositories/:id
```
* The route must delete the repository with the id present in the route parameters;

```
POST/repositories/:id/
```
* like: The route must increase the number of likes from the specific repository chosen through the id present in the route parameters, at each call of this route, the number of likes must be increased by 1;


## Testing specification

### For this challenge we have the following tests:

* should be able to create a new repository.
* should be able to list the repositories
* should be able to update repository.
* should not be able to update a repository that does not exist.
* should not be able to update repository likes manually.
* should be able to delete the repository
* should not be able to delete a repository that does not exist
* should be able to give a like to the repository
* should not be able to like a repository that does not exist

## Integrations
## CI
This project is integrated with a continuous integration tool [Circle Ci](https://circleci.com/) for feedback on improvements and execution of tests, a new build is launched at each commit for the main branch. <br/> <br/>
![CircleCI](https://img.shields.io/circleci/build/github/heziofernandes/gostack-api-nodejs/master) 
## Code Analise
There is also integration with a code analysis tool, [Code Climate](https://codeclimate.com/) where it is possible to measure the level of project maintenance and other standards of good practice. <br/> <br/>
![Code Climate](https://img.shields.io/codeclimate/maintainability/heziofernandes/gostack-api-nodejs)
