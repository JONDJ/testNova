## DEVOPS Technical Assessment 

This project is developed in Laravel framework 8, provides a REST endpoint named: /DevOps

Github repository

- https://github.com/JONDJ/testNova.git

Demo in Google Cloud
- [https://novadevops.rj.r.appspot.com/api/DevOps](https://novadevops.rj.r.appspot.com/api/DevOps)
- [https://novadevops.rj.r.appspot.com/](https://novadevops.rj.r.appspot.com/)


## Test requirements

- *The microservice must be containerized and can be deployed on any machine or in the cloud.*

    **In the workflow, the build runs on the last version of ubuntu and the demo is published in Google cloud with App Engine**

- *It is required to use a load balancer with a minimum of two nodes with the same microservice.*

    **In the Google Cloud is created the CLOUD LOAD BALANCING**
- *The infrastructure code must be versionated*
    
    **The Project us GIT and you can check the GitHub repository**

- *The pipeline should be configured as a code and needs to be stored in a repository.*
    
    **The pipeline CI/CD is stored in .github/workflows/buidl.yml**

- *It should have two stages at minimum: “build” and “test” and can have the stages that you want.*

    **The project Has Tests(Feature/Unit)**

- *Must be automatic and can be executed by any branch, the master branch always deploys to the 
production environment. If it is required, you can create more environments: development or
testing. Additionally, you could execute the pipeline on demand, and you can deploy any version*

    **Project have two branchs(development and master)**

## Screenshot

![Request](https://magawb.com/test/storage/request.jpg)
