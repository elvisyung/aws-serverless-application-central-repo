# AWS Serverless Application Central Repository

The frontend of this application was developed using React (Typescript) while the backend was developed using Typescript. 

The CI/CD pipeline was also developed using Typescript and intends to stage stacks for testing, production and deployment while catching bugs during different builds with unit tests written in Jest integrated - units tests for lambda functions and SNS topics were integrated as well. 

This project also utilises Cloudwatch to monitor stacks for events triggering API endpoints, which generates alarms to an SNS topic and activates a webhook Lambda to send HTTP calls to Slack - alerting developers of real-time issues.  

AWS Serverless Application Repo Links 

Frontend: https://github.com/elvisyung/aws-serverless-application-frontend

Backend: https://github.com/elvisyung/aws-serverless-application-backend

CI/CD Pipeline: https://github.com/elvisyung/aws-serverless-application-cicd
