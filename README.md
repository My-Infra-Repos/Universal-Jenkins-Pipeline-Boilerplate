This is a Jenkinfile boilerplate used to do deployment in various eks clueters & environments.
==================================================================================================
### What it contains
1. #### This is a complete CI-CD Jenkins pipeline which we can customize as per our need. It can be used to deploy the releases in diffrenet environments where EKS is running in AWS for different environments.

2. #### It use to accept an environment.json file which contains all of the data specific to you your environment

#### How it can be used ?
Follow the below steps
`` `````
~~~
       1. Clone the repo.
       2. Open environment.json file in some editor & replace the values specififc to your environment.
       3. Also select the relevant environments in environment.json file along with Jenkinsfile.
       4. Make sure the EKS should be existing.
       5. Copy the environment files inside your repo.
       6. create the jenkin job with our jenkins file.
~~~
````
``

