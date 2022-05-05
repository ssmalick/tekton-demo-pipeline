# Demo pipeline

Simple pipeline to deploy and promote application.


## DEV pipeline

**Steps**

1. Clone the application source
2. Build the source
3. Build and push the container image to remote repository
4. Update application config manifest


## QA pipeline

**Steps**

1. Get container digest currently running in lower env (DEV)
2 Deploy the container

This pipeline can also deploy a specific container image digest
