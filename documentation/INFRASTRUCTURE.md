## INFRASTRUCTURE

---
#### Udagram
The infrastructure used to build Udagram is outlined in the README.md file. 
Succinctly put, it is built with Angular, Node, and ExpressJS.

#### Udagram Cloud Infrastructure
Udagram is hosted on AWS across three different services:
- S3: used for web hosting
- Elastic Beanstalk: used for API
- RDS: used for database

Additionally, Udagram is run through a CircleCi pipeline that builds and deploys the app from the '/udagram' folder
after every push to the master/main branch. This pipeline has all relevant environment variables to be able to 
connect to the DB, access the API, have valid AWS credentials and so forth.