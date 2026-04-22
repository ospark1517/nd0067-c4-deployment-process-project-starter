## DEPENDENCIES

#### Frontend
The frontend of Udagram uses the following dependencies. Version specifications are given and full details
may be found in the /udagram/udagram-frontend/package.json file.


DEPENDENCIES
- Angular (@angular/common, @angular/core, @angular/forms, etc.) - ^8.2.14,
- Ionic native (@ionic-native/core, @ionic-native/splash-screen, @ionicnative/status-bar) - ^5.0.0
- Ionic Angular (@ionic/angular) - ^4.1.0
- core-js - ^2.5.4
- rxjs - 6.5.4
- zone.js - 0.9.1

DEV DEPENDENCIES
- Angular CLI - 8.3.25
- Angular compiler CLI (@angular/compiler, @angular/compiler-cli) - ^8.2.14
- Jasmine - 2.99.1
- Karma - 3.1.4
- Protractor - 5.4.0
- ts-node - 8.0.0
- tslint - 5.12.0
- typescript - 3.5.3


#### API
The API of Udagram uses the following dependencies. Version specifications are given and full details
may be found in the /udagram/udagram-api/package.json file.

DEPENDENCIES
- aws-sdk - ^2.429.0
- bcryptjs - 2.4.3
- body-parser - ^1.18.3
- cors - ^2.8.5
- dotenv - ^8.2.0
- email-validator - ^2.0.4
- express - ^4.16.4
- jsonwebtoken - ^8.5.1
- pg - ^8.7.1
- reflect-metadata - ^0.1.13
- sequelize - ^6.26.0
- sequelize-typescript - ^2.1.5

DEV DEPENDENCIES
- chai - ^4.2.0
- chai-http - ^4.2.1
- eslint - ^6.8.0
- eslint-config-gooel - ^0.14.0
- mocha - ^6.1.4
- ts-node-dev - ^1.0.0-pre.32
- typescript ^4.2.3


#### DEPLOYMENT
To deploy, Udagram uses the AWS CLI, EB CLI, and CircleCi connected to the appropriate repo in GitHub.
When running "aws config", you will need to provide:

- Access Key ID
- Secret Access Key ID
- Session Token

The default region is "us-east-1" and there is no specified output.
All of the values above were given by Udacity.
Given that these access keys and session tokens are temporary, the user may have to 
configure every so often with updated keys and tokens. T
HESE MUST BE THE SAME AS THOSE SPECIFIED IN THE CIRCLE CI ENVIRONMENT VARIABLES


#### Hosting/Infrastructure
Udacity is hosted on AWS using the following services:
- S3 for web hosting
- Elastic Beanstalk for APIs
- RDS for the database
