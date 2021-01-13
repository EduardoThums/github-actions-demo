# GitHub Actions Demo

Simple demo used to learn how to configure and use GitHub Actions.

## Workflow

The workflow is divided into two parts, the first is responsible to build the application and the second to deploy using [Heroku](https://dashboard.heroku.com/) platform.

### Build
The application dependencies are installed and them using maven it's created a executable JAR file.

### Deploy
Using the Heroku CLI with repository secrets to store the authentication key, the JAR file is deployed. The application can be access [here](https://et-github-actions-demo.herokuapp.com/). 
