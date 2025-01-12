# Project 7: Continous Delivery With Jenkins


[*Project Source*](https://www.udemy.com/course/devopsprojects/?src=sac&kw=devops+projects)


## In project 6 we did our Continous Integration Pipeline now we will do our Continous Delivery part and below is the Architecture

![Architecture](images/Continous-Delivery-of-Java-Web-Application.png)

## Before We start our Continous Delivery Journey We will need below services,tools and plugins.
1. AWS:

   - IAM USER With ACCESS Key
   - ECR Registry (Docker registry from AWS)

2. Plugins in Jenkins:

   - docker
   - docker pipeline
   - ECR
   - AWS SDK

3. Tools in Jenkins EC2:
   - Store AWS access keys(credentials)
   - Install Docker Engine in Jenkins
   - Install AWSCLI


