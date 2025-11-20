# Deployment Pipeline to Render

This app is for testing a CI/CD Pipeline to Render and Heroku. More targets might be added later. Each target has their own workflow and branch. Pushing to heroku branch initiates the workflow in heroku-deploy.yml and so on.

## Setup

Fork the project and configure the secrets accordingly to each environment. Create the required webhook in Render and/or the app with Github pipeline in Heroku.
