# AWS Project Used In Production | Complete Implementation
### This project involves creating a production-ready VPC with servers deployed across two Availability Zones for resiliency, using an Auto Scaling group and Application Load Balancer. The servers, placed in private subnets, receive traffic through the load balancer and access the internet via NAT gateways in both Availability Zones for added reliability.

[*Project Source*](https://www.youtube.com/watch?v=FZPTL_kNvXc&list=PLdpzxOOAlwvLNOxX0RfndiYSt1Le9azze&index=9)


![Architecture](images/AWS-Project-Used-In-Production.png)

## Step-1: Create VPC
![vpc](images/vpc.png)


## Step-2: Auto Scaling group
![Auto Scaling group](images/auto-scaling.png)

## Step-3: Bastion host setup 
![copying pem file](images/copying-pem-file.png)

![pemfile in bastion host](images/pem-file-in-bastionhost.png)

![connecting to private subnet](images/connection-to-private-ec2-from-bastion.png)

## Step-4: Load Balancer
![Load Balancer](images/load-balancer.png)

![Load Balancer Active](images/load-balancer-active.png)

## Step-5: Cleanup
Now clean Everything in order to prevent charges from AWS
