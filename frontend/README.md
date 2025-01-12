# Provectus Internship Program test assignment
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)
### Test Assignment
The following is a solution for hard's difficulty in front-end internship

This application was built using React, React-Native, and TypeScript stack.

You can display, update, add, delete expenses and see total amount spent by month and category

#### Forms are validated:

1. Amount must be a positive number and a non empty field

2. No restriction on description except being a non empty field

3. No validation for date and category because pickers were used with initial value so no room for user's mistakes

#### Finally, you can run the database,server and client using one command 
```
docker-compose up --build
```
#### Client application will be available at:
```
http://localhost:3000/
```

### Getting Started
##### Clone the repo 
```
https://github.com/Karam19/internship
```
##### Move to exercise folder
```
cd ./internship/frontend/exercise
```
##### Seed the database with the generated data
```
docker-compose up mongo-seed
```
##### Start the api server
```
docker-compose up api
```
##### Start the client-side
```
docker-compose up --build react
```
##### You can run both the back-end and front-end using one command:
```
docker-compose up --build
```
#### Check the api doc generated by the server side
```
http://localhost:5000/api-docs
```
![Api](./swagger.png)
## Acceptance criteria
___
#### Difficulty level : **Easy**
- Minimalistic UI implemented to display / create / update / delete expences
- UI displays a chart that shows spending stats/statistics by month and spending category
- Comprehensive documentation to launch the application
#### Difficulty level : **Medium**
- The application is written in TypeScript
- Form input is validated
#### Difficulty level : **High**
- Created Docker image for the front-end application
- The docker-compose file is updated and can be used to run the whole app with one command
-
## How to Apply

1. Have a Github account & basic Git skills
2. Fork & clone this repository
3. Complete the assignment in a separate branch
4. Push the branch and open a PR to this repository
5. Fill in the [application form](https://www.surveymonkey.com/r/InternshipProvectus), add a link to your PR, submit.
