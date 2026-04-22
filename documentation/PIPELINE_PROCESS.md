## PIPELINE PROCESS

Udagram uses CircleCi as its CI/CD pipeline. The steps it undertakes are as follows:

1. Build
2. Hold (for manual approval)
3. Deploy

If done successfully, all relevant resources will be deployed to our AWS resources.
This pipeline is triggered after any push to the main/master branch of the Udagram repo.