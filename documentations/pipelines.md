## Udagram Pipeline
![circleci](circleci-lifecycle.png)

There are 9 jobs in the .circleci/config.yml to run, build and deploy the project, frontend and backend, CircleCI reads this file and starts the sequential workflow.

### Scripts running through workflows 
- Front-end Install: ```npm run frontend:install```
- Front-end Run: ```npm run frontend:start```
- Front-end Build: ```npm run frontend:build```
- Front-end Deploy: ```npm run frontend:deploy```
- Back-end Install: ```npm run api:install```
- Back-end Build: ```npm run api:build```
- Back-end Run: ```npm run api:start```
- Back-end Deploy: ```npm run api:deploy```
- Depoly the whole project: ```npm run deploy```