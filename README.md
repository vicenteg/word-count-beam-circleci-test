This repo contains a simple Apache Beam pipeline and a CircleCI configuration that does the following:

- Obtain Java dependencies
- Run tests
- Deploy the batch pipeline

This is a simple example of how you might use CircleCI to build and test a Beam pipeline before running it on the Dataflow service.

You'll need to set some environment variables in CircleCI:

```
DATAFLOW_TEMP_BUCKET
GCLOUD_SERVICE_KEY
GOOGLE_COMPUTE_ZONE
GOOGLE_PROJECT_ID
``` 

Use the instructions below to set up GCP authentication for this project:

https://circleci.com/docs/2.0/google-auth/

And follow the instructions here to obtain the value to place in the variable:

https://circleci.com/docs/2.0/env-vars/#setting-an-environment-variable-in-a-project

