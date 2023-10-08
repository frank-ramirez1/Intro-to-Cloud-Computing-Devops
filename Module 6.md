# Module 6 

## AWS Compute Services

### Amazon EC2 
#### - Key Concepts
  ##### - Infrastructure as a service (IaaS)
  ##### - Instance-based
  ##### - Virtual machines
#### - Characteristics 
  ##### - Provision virtual machines that you can manage as you choose
#### - Ease of Use
  ##### - A familiar concept to many IT professionals

### AWS Lambda 
#### - Key Concepts 
  ##### - Severless computing 
  ##### - Function-based
  ##### - Low cost
#### - Characteristics 
  ##### - Write and deploy code that executes on a schedule or that can be triggered by events
  ##### - Use when possible (architect for the cloud)
#### - Ease of use
  ##### - A relatively new concept for many IT staff members, but easy to use after you learn how
#### Amazon ECS 
#### Amazon EKS
#### AWS Fargate 
#### Amazon ECR
##### - Key Concepts
  ###### - Container-based computing
##### - Characteristics
  ###### - Spin up and execute jobs more quickly
##### - Ease of use 
  ###### - AWS Fargate reduces administrative overhead, but you can use options that give you more control

### AWS Elastic Beanstalk
#### - Key Concepts 
  ##### - Platform as a service (PaaS)
  ###### - For web applications
#### - Characteristics
  ##### - Focus on your code (building your application)
  ###### - Can easily tie into other services- databases, domain name systems(DNS) etc
#### - Ease of use
  ##### - Fast and ease to get started

### Some aspects to consider
#### - what is your application design
#### - What are your usage patterns
#### - Which configuration settings will you want to manage

## Amazon EC2
 
### Common usages
#### - app, web, database, game, mail, media, catalog, file, computing and proxy servers

### Can use any OS (windows or Linux) instance

### AMI (Amazon Machine Image) - is a template that is used to create an EC2 instance (which is virtual machine, or VM that runs in the AWS cloud)

### Tags enable you to categorized in different ways 

### Security group acts as a virtual firewall to an instance 

### CloudWatch monitors instances
#### - provides near-real-time metrics
#### - Providers charts in the Amazon EC2 console monitoring tab that you can view
#### - Maintains 15 months of historical data

### Basic monitoring 
#### - default no additional cost
#### - Metric data sent to CloudWatfch every 5 minutes
### Detailed monitoring
#### - Fixed monthly rate for sever pre-selected metrics
#### - Metric data delivered every 1 minute

### Containers are a method of operating system virtualization

#### Benefits
##### - Repeatable
##### - Self-contained environments
##### - Software runs the same in different environments
  ###### - Developers laptops, test, production
##### - Faster to launch and stop or terminate than virtual machines

### Docker - is a software platform that enables you to build, test, and deploy applications quickly

### You can run containers on Docker
#### - Containers are created from a template called an image

### A container has everything a software application needs to run

## Amazon ECS 
### - highly scalable, fast, container management service

### Key Benefits
#### - orchestrates the running of Docker containers
#### - Maintains and scales the fleet of nodes that run your containers
#### - Removes the complexity of standing up the infrastructure 

## Kubernetes
### - open source software for container orchestration 
### - Deploy and manage containerized apps at scale
### - Automates container provisioning 

## Amazon Elastic Container Registry
 ### -fully managed docker container registry that makes it easy for developers to store, management and deploy docker container settings

## AWS Lambda
### - Serverless compute service
### - It supports multiple programming languages 
### - Completely automated administration 
### - Built-in fault tolerance
### - It supports the orchestration of multiple functions
### - Pay-per-user 

## Lambda Soft limits per region
### - Concurrent executions =1000
### - Function and layer storage = 75 GB

## Lambda Hard limits for individual functions:
### - Maximum function memory allocation = 10,240 MB
### - Function timeout = 15 minutes
### - Deployment package size = 250 MB unzipped, including layers
### - Container image code package size = 10 GB

## AWS Elastic Beanstalk
### - An easy way to get web apps up and running
### - Automatically handles
  #### - Infrastructure provisioning and configuration
  #### - Deployment 
  #### - Load balancing
  #### - Automatic scaling 
  #### - Health monitoring
  #### - Analysis and debugging
  #### - Logging
