## DIAGRAM

#### CI/CD Pipeline Flow:
The following diagram illustrates the flow of actions that happen once the user interacts with the CircleCi CI/CD pipeline:


User pushes to master -> GitHub -> CircleCi Pipeline -> S3 frontend is updated and deployed
                                        |
                                        |- > Elastic Beanstalk is deployed

Once the user pushes new code to the master branch of Udagram, GitHub is updated which then triggers the CircleCi pipeline to deploy new resources to the S3 bucket and Elastic Beanstalk.


#### User Interaction Flow:
The following diagram illustrates the flow of events that occur when the user attempts to interact with Udagram on browser (making a post, logging in, signing up, etc.):

User event -> S3 Bucket -> Elastic Beanstalk API -> RDS Database

The user interacts with the website via the S3 bucket hosting function, triggering the API to connect to the RDS database in order to supply the necessary resources to complete this action.

