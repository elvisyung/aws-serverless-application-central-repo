# AWS Serverless Application Central Repository

The application's front end uses React with TypeScript, paired with a TypeScript backend.

The CI/CD pipeline, built with TypeScript, stages stacks for testing, production, and deployment while running Jest unit tests to detect issues. These tests cover Lambda functions and SNS topics.

This project employs CloudWatch to monitor stacks for API-triggered events, generating alerts sent to an SNS topic. Additionally, a webhook Lambda notifies developers of real-time issues via Slack.

AWS Serverless Application Repo Links 

Frontend: https://github.com/elvisyung/aws-serverless-application-frontend

Backend: https://github.com/elvisyung/aws-serverless-application-backend

CI/CD Pipeline: https://github.com/elvisyung/aws-serverless-application-cicd
