## Pipeline process

We have one workflow which runs two jobs:

-   `build` which install and build both the front-end and back-end applications.
-   `deploy` which deploy the front-end to AWS S3 using aws cli and deploy the back-end to Elastic Beanstalk using eb.
-   The `deploy` job depends on the `build` job.
-   I've also added AWS Credentials to Circle ci environment variables which are used by aws cli for deployment.
