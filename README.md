# pets-router

Router app for the Pets-service application

## Deployment

1. Create xsuaa service in the Cloud Foundry

`cf create-service xsuaa application pets-xsuaa -c xs-security.json`

2. Deploy application router to the Cloud Foundry

`cf push`

3. Bind pets-xsuaa service to your main app