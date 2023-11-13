# Nomad E-commerce store API

This repo contains the Nomad E-commerce store API server project files.

## Cloning API files
- We clone the api repo we will be using: `git clone git@github.com:cagarweyne/devops-masterclass-api-starter.git nomad-store-api`
- Adding content to the `ci.yml` file for the continuous integration, specifying the AWS access key and password, also defining the region
- In order to push changes to github we need to create a new repo in github (make it public to have available the Environments features)
- Since we are having 2 environments we need to into github in the browser > settings > Environments > New Environment: `nomad-stage` and `nomad-prod` for this one we also need **required reviewers**
- Lets add secrets for the `nomad-stage` environment: GitHub > Settings > Environments > `nomad-stage` > Environment secrets
```
   AWS_ACCESS_KEY_ID
   AWS_SECRET_ACCESS_KEY
   AWS_DEFAULT_REGION
```
- 