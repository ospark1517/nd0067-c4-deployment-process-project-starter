## DIAGRAM

#### CI/CD Pipeline Diagram:
The following diagram illustrates the flow of actions that happen once the user interacts with the CircleCi CI/CD pipeline:


[Developer]
     |
     v
[GitHub Repository]
     |
     v
[CircleCI Pipeline]
     |--------------------> [S3 Bucket - Frontend Deploy]
     |
     +--------------------> [Elastic Beanstalk - API Deploy]
                                   |
                                   v
                           [RDS PostgreSQL Database]



#### Infrastructure Diagram:
The following diagram illustrates the flow of events that occur when the user attempts to interact with Udagram on browser (making a post, logging in, signing up, etc.):

[User Browser]
      |
      v
[S3 Bucket - Frontend Hosting]
      |
      v
[Elastic Beanstalk - API]
      |
      v
[RDS PostgreSQL Database]





