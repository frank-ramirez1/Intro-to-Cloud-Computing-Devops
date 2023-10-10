# Module 1 - Cloud Concepts Overview

### Cloud computing the the on demand delivery of compute power, database, storage, applications and other resource over the internet

### Cloud computing is pay as you go

### Procurement time reduced drastically 

### Resources can be increased or decreased as needed

### There are different types of cloud service models
#### - IaaS (infrastructure as a service)
  ##### - Highest level of control
  ##### - Similar to traditional IT models
#### - Pass (platform as a service)
  ##### - Removes the need to manage OS and Hardware
#### - SaaS (software as a service)
  ##### - Is end-users applications 
  ##### - Less control over IT

### Three cloud deployment models 
#### - Cloud 
#### - Hybrid
#### - On-premises (Private cloud)

### Six benefits of cloud computing  
#### - Trade capital expense for variable expense
#### - Massive economies of scale
#### - Stop guessing capacity 
#### - Increased speed and agility
#### - Stop spending money on running and maintaining a data center 
#### - Go global in minutes

## Intro to AWS

### Web service is any piece of software that makes itself available on the internet or private network

### AWS is managed by AWS management console, AWS CLI and software development kits

### Services fall under different categories which depend on business goals and tech requirements 

## Moving to AWS Cloud

### AWS cloud adoption framework - provide guidance and best practices to help organizations

## It is organized into six perspectives
### Business Capabilities
#### - Business
#### - People
#### - Governance
### Technical Capabilities
#### - Platform
#### - Security
#### - Operations

#Module 2 - Cloud Economics and Billing

## Fundamentals and Pricing

### Three fundamental cost of AWS
#### - Compute
  ##### - Charged per hour/second
  ##### - Varies by instance type
#### - Storage
  ##### - Charged typically per GB
#### - Data Transfer
  ##### - Outbound is aggregated and charged
  ##### - Inbound has no charge (with some exceptions)
  ##### - Charged typically per GB

### There a volume based discounts
### Benefit from growing economies of scale

### Some services are no additional charge
#### - Amazon VPC
#### - Elastic Beanstalk
#### - Auto Scaling
#### - AWS CloudFormation
#### - AWS identity and Access Management (IAM)

### Total Cost of Ownership 
#### - Financial estimate to help identify direct and indirect cost of a system

### AWS Pricing Calculator helps with 
#### - Estimate monthly cost
#### - Identify opportunities to reduce monthly cost
#### - Model your solutions before building

## AWS Organizations

### Allows consolidation of multiple accounts 

### AWS Organizations Enables organizations to have:
#### - policy-based account management
#### - Group based account management 
#### - Application programming interfaces (APIs) that automate account management 
#### - Consolidated billing

### AWS Organizations does not replace using AWS Identity and Access Management 

### IAM policies allow and denies access to AWS services for users, groups and roles

### Service control policies (SCPs) enable you to allow or deny access to AWS services for individual or group accounts in an OU

### Steps to create to use AWS Organizations
#### 1. create organization
#### 2. Create organizational units
#### 3. Create service control policies
#### 4. Test restrictions

### It can be managed by different interfaces
#### - AWS Mangement Console
#### - AWS CLI tools
#### - Software development kits (SDKs)
#### - HTTPS query application programming interfaces (API)

## AWS Billing & Cost Management

### - Service to pay bills and monitor usage
### - AWS Billing Dashboard provides high-level of how cost are tending

### there are several other cost management tools
#### - AWS Budget
#### - AWS Cost and Usage Report
#### - AWS Cost Explorer

## Technical Support Models

### AWS Support
#### - Proactive guidance:
  ##### - Technical Account Manager (TAM)
   ###### - Primary point of contact 
   ###### - Provide guidance, architectual review
#### - Best practices:
  ##### - AWS Trusted Advisor
   ###### - Automated service that acts as a customized cloud expert, online resource to help with productivity and lowering cost.
#### - Account assistance:
   ##### - AWS Support Concierge
   ###### - Addresses non-technical, billing and account level inquiries

### Support plans
#### - Basic Support: Resource Center access, Service Health Dashboard, product FAQs, discussion forums, and support for health checks
#### - Developer Support: Support for early development on AWS
#### - Business Support: Customers that run production workloads
#### - Enterprise Support: Customer that run business and mission-critical workloads.

# Module 3 AWS Global Infrastructure

### AWS Region is a physical geographical location

### Each region provides full redundancy and connectivity to the network

### A region usually consist of two or more Availability Zones

### Availability zones usually have one or more data center

### Data is not replicated automatically across different regions
#### - This needs to be done by the client

### AWS Management console can be used to enable or disable regions

### Factors when selecting a region
#### - Data governance, legal requirements
#### - Proximity to customers (Latency)
#### - Services available within the region
#### - Cost (vary by Region)

### Availability Zones are fully isolated partitions of the AWS infrastructure 

### AWS recommends replicating data and resources across Availability Zones for resiliency

### AWS data centers are designed for security

### Data centers have redundant power, networking, and connectivity and is housed in a separate facility

### Data centers usually have 50,000 to 80,000 physical servers

### Original Design Manufacturers or ODMs design and manufacture products based on specifications from a second company

## Amazon Cloudfront -  is a content delivery network used to distribute content to end user to reduce latency

### AWS infrastructure features
#### - Elasticity and Scalability
  ##### - Elastic infrastructure; dynamic adaption of capacity
  ##### - Scalable infrastructure; adapts to accommodate growth
#### - Fault-tolerance
  ##### - Continues operating properly in the presence of a failure
  ##### - Built-in redundancy of components
#### - High availability 
  ##### - High level of operational performance
  ##### - Minimize downtime
  ##### - No human intervention

## AWS Services and Service Categories

### AWS has 23 service categories 
#### - Each category contains one or more services

### Most widely used services

### AWS Storage services
#### - Amazon S3
#### - Amazon EBS
#### - Amazon EFS
#### - Amazon S3 Glacier

### AWS Computer services
#### - Amazon EC2 
#### - Amazon EC2 Auto Scaling
#### - Amazon Elastic Container Service
#### - Amazon EC2 Container Registry
#### - AWS Elastic Beanstalk
#### - AWS Lambda
#### - Amazon EKS
#### - AWS Fargate

### AWS Database services
#### - Amazon Relational Database Services
#### - Amazon Aurora
#### - Amazon Redshift
#### - Amazon DynamoDB

### AWS Networking and Content delivery services
#### - Amazon VPC
#### - Amazon Load Balancing 
#### - Amazon CloudFront
#### - AWS Transit Gateway
#### - Amazon Route 53
#### - AWS Direct Connect
#### - AWS VPN

### AWS security, identity, and compliance services
#### - AWS IAM
#### - AWS Organizations
#### - Amazon Cognito
#### - AWS Artifact
#### - AWS Key Management Service
#### - AWS Shield

### AWS cost management services
#### - AWS Cost and Usage Report
#### - AWS Budgets
#### - AWS Cost Explorer

### AWS management and governance services
#### - AWS Management Console
#### - AWS Config
#### - AWS CloudWatch
#### - AWS Auto Scaling
#### - AWS CLI
#### - AWS Trusted Advisor
#### - AWS Well-Architected Tool
#### - AWS CloudTrail

#Module 4 - AWS Cloud Security

## AWS Shared Responsibility Model
#### - AWS is responsible for security of the cloud
#### - Customers are responsible for securing every app and data set that they implement in the cloud
#### - AWS Secures Software, hardware and networking 
#### - Customer is responsible for data at rest and transit 
#### - Customer should secure the firewall and passwords

### Examples of services managed by the customer
#### - Amazon EC2
#### - Amazon Elastic Block Store
#### - Amazon Virtual Private Cloud

### Examples of services managed by AWS
#### - AWS Lambda 
#### - Amazon Relational Database Service
#### - AWS Elastic Beanstalk

### Infrastructure as a service (IaaS)
#### - Customer has more flexibility over configuration networking and storage
#### - Customer is responsible for managing more aspects of the security
#### - Customer configures the access controls

### Platform as a Service (PaaS)
#### - Customer does not need to manage the underlying infrastructure
#### - AWS handles the os, db, patching, firewall config, and disaster recovery
#### - Customer can focus on managing code or data

### Software as a Service (SaaS)
#### - Software is centrally hosted
#### - Licensed on a subscription model or pay-as-you-go basis
#### - Services are typically accessed via web browser, mobile app, or application programming interface (API)
#### - Customers do not need to manage the infrastructure that supports the service

## AWS IAM

### Identity and Access Management (IAM) is a free service

### IAM Essential components 
#### - IAM User: A person or application that can authenticate with an AWS account
#### - IAM group: A collection of IAM user that are granted identical authorization
#### - IAM Policy: The documentation that defines which resources can be accessed and the level of access to each resource
#### - IAM role:Useful mechanism to grant a set of permissions for making AWS service request

### By default users do not have access to anything 

### IAM Policy- is a document that defines permissions 

### Two types of policies
#### - identity based: attached to user, group, or role
#### - Resource based: attached to a resource (not a user, group, or role)

### IAM Group - a collection of IAM users

### IAM Role - is an IAM identity with specific permissions 
#### - Roles do not have standard credentials

## AWS Securing a New Account

#### - While logged in as root user create an IAM user for yourself. Save access keys if needed
#### - Create an IAM  group, give it full access permissions, and add the IAM user to the group
#### - Disable and remove your account root user access keys, if they exist 
#### - Enable password policy for users
#### - Sign in with your new IAM user credentials
#### - Sign in with new IAM user 
#### - Store your account root user credentials in a secure place

## CloudTrail 
#### - tracks activity on your account
#### - Logs all API interactions

## Securing Accounts

### AWS Organizations
##### - Allows you to group multiple accounts into OUs

#### Service Control Policies - offer centralized control over accounts.

### AWS Key Management Service (AWS KMS) 

#### - Enables you to create and manage encryption keys
#### - Enables you to control the use of encryption across AWS services and in your applications
#### - Integrates with AWS CloudTrail to log all key usage

### Amazon Shield
#### - Is a managed distributed denial of service (DDoS) protection service
#### - Safeguards applications running on AWS
#### - Provides always-on detection and automatic inline mitigations 
#### - AWS Sheild Standard enabled for at no additional cost. AWS Shield Advanced is an optional paid service.

### Securing Data
#### Encryption can be enabled

#### By default all S3 buckets are private and protected

### AWS Config
#### - Assess, audit, and evaluate the configurations of AWS resources
#### - Use for continuous monitoring of configurations
#### - Review configuration changes
#### - View detailed configurations histories
#### - Simplify compliance auditing and security analysis

# Module 5 Networking and Content Delivery 

## Networking Basics

### Networking requires a router or a switch

### Each machine has a unique I.P Address

### 32 bit address is a IPV4 address

### 128 bit address is an IPV6 Address

### Amazon VPC
#### - Enables you to provision a logically isolated section of the AWS Cloud where you can launch AWS resource in a virtual network that you define
#### - Gives you control over your virtual networking resources
  ##### - Selection of IP address range
  ##### - Creation of subnets
  ##### - Configuration of route tables and network gateways
#### - Enables you to customize the network configuration for your VPC
#### - Enables you to use multiple layers of security

### A VPC is a virtual network that is isolated from other VPCs 

### Once an I.P range has been assigned in a VPC you cannot change it

### An elastic network interface is a virtual network interface that you can 
#### - Attach to an instance
#### - Detach from the instance, and attach to another instance to redirect network traffic

### A route table contains a set of rules that you can configure to direct network traffic from your subnet

### Each route specifies a destination and target 

### By default every route table contains a local route for communication within the VPC 

### Each subnet must be associated with a route table 

## VPC Networking

### Internet gate way 
#### - provides a target in VPC route tables for internet traffic 
#### - To perform network address translation for instances that were assigned public IPv4 addresses

### VPC peering allows you to connect your own AWS account between accounts, or between regions

### VPC Restrictions 
#### - IP spaces cannot overlap
#### - Transitive peering is not supported
#### - You can only have one peering resource between the same two VPCs

### VPC security

#### Security group acts as a virtual firewall inbound and outbound 
##### - Security groups have rules to manage instance traffic
##### - Default security groups are sealed shut to inbound traffic. We need to define rules
##### - Security groups are stateful. The outbound traffic is always allowed 

#### Network ACLs
##### - A network ACL has separate inbound and outbound rules, and each rule can either allow or deny traffic
##### - Default network ACLs allow all inbound and outbound IPv4 traffic 
##### - Network ACLs are stateless

#### Amazon Route 53
##### - gives you the ability to register a domain name
##### - Is a highly available and scalable domain name system (DNS) web service
##### - Is used to route end users to internet applications by translating names into numeric IP addresses that computers use to connect to each other
##### - Is fully compliant with IPv4 and IPv6
##### - Connects user request to infrastructure running in AWS and also outside of AWS 
##### - Is used to check the health of your resources
##### - Features traffic flow
##### - Enables you to register domain names

#### Supported Routing
##### - Simple routing: use in single-server environments 
##### - Weighted routing: assign weights to resource record sets to specify the frequency 
##### - Latency routing: help improve your global applications
##### - Geolocation routing: route traffic based on location of your users
##### - Geoproximity routing: route traffic based on location of your resources
##### - Failover routing: fail over to a backup site if your primary site becomes unreachable 
##### - Multi value answer routing: respond to dns queries with up to eight healthy records selected at random

#### Amazon Router 53 DNS failover
##### - improve the availability of your applications that run on AWS by:
  ###### - Configure backup and failover scenarios for your own applications
  ###### - Enabling high available multi-region architectures on AWS 
  ###### - Creating health check

#### Amazon CloudFront
##### - fast, global, and secure content delivery service
##### - Global network of edge locations and regional edge caches
##### - Self-service model
##### - Pay-as-you-go pricing 

#### Edge locations - network of data centers that CLoudFront uses to serve popular content quickly to customers

#### Regional edge cache - CloudFront locations that caches content that is not popular enough tot stay at an edge location. It is located between the origin server and the global edge location


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

### Amazon ECS 
### Amazon EKS
### AWS Fargate 
### Amazon ECR
#### - Key Concepts
  ##### - Container-based computing
#### - Characteristics
  ##### - Spin up and execute jobs more quickly
#### - Easde of use 
  ##### - AWS Fargate reduces administrative overhead, but you can use options that give you more control

### AWS Elastic Beanstalk
#### - Key Concepts 
  ##### - Platform as a service (PaaS)
  ##### - For web applications
#### - Characteristics
  ##### - Focus on your code (building your application)
  ##### - Can easily tie into other services- databases, domain name systems(DNS) etc
#### - Ease of use
  ##### - Fast and ease to get started

#### Some aspects to consider
##### - what is your application design
##### - What are your usage patterns
##### - Which configuration settings will you want to manage

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

### Benefits
#### - Repeatable
#### - Self-contained environments
#### - Software runs the same in different environments
  ##### - Developers laptops, test, production
#### - Faster to launch and stop or terminate than virtual machines

### Docker - is a software platform that enables you to build, test, and deploy applications quickly

### You can run containers on Docker
#### - Containers are created from a template called an image

### A container has everything a software application needs to run

### Amazon ECS 
#### - highly scalable, fast, container management service

### Key Benefits
#### - orchestrates the running of Docker containers
#### - Maintains and scales the fleet of nodes that run your containers
#### - Removes the complexity of standing up the infrastructure 

### Kubernetes
#### - open source software for container orchestration 
#### - Deploy and manage containerized apps at scale
#### - Automates container provisioning 

### Amazon Elastic Container Registry
 #### -fully managed docker container registry that makes it easy for developers to store, management and deploy docker container settings

## AWS Lambda
#### - Serverless compute service
##### - It supports multiple programming languages 
##### - Completely automated administration 
##### - Built-in fault tolerance
##### - It supports the orchestration of multiple functions
##### - Pay-per-user 

### Lambda Soft limits per region
#### - Concurrent executions =1000
#### - Function and layer storage = 75 GB

### Lambda Hard limits for individual functions:
#### - Maximum function memory allocation = 10,240 MB
#### - Function timeout = 15 minutes
#### - Deployment package size = 250 MB unzipped, including layers
#### - Container image code package size = 10 GB

## AWS Elastic Beanstalk
#### - An easy way to get web apps up and running
#### - Automatically handles
  ##### - Infrastructure provisioning and configuration
  ##### - Deployment 
  ##### - Load balancing
  ##### - Automatic scaling 
  ##### - Health monitoring
  ##### - Analysis and debugging
  ##### - Logging

# Module 7

## Storage

### Cloud storage is normally more reliable than traditional storage

## Amazon EBS
### Provides persistent block storage volumes for amazon EC2

### Difference between storage types is whether they allow block storage or object storage

### Amazon EBS offers block level storage

### Volumes are automatically replicated within its Availability zone

### It can be backed up automatically to amazon S3 through snapshots

### Snapshots
#### - Point in time snapshots
#### - Recreate a new volume at any time

### Encryption
#### - encrypted amazon EBS volumes
#### - No additional cost

### Elasticity
#### - increase capacity
#### - Change to different types

### Amazon Simple Storage Service (Amazon S3)

### You get fine grade control over who access the data

### Amazon Elastic File System (Amazon EFS)

### Implements storage for EC2 instances is a shared files system

### Amazon EFS Features
#### - Works well for big data and analytics, media processing workflows, content management, web serving, and home directories
#### - Petabyte-scale, low-latency file system
#### - Shared storage
#### - Elastic capacity
#### - Supports Network File System (NFS) versions 4.0 and 4.1 (NFSv4)
#### - Compatible with all Linux-based AMIs for Amazon EC2

### Can be scaled from Gigabytes to Petabytes

### Amazon EFS implementation
#### - Create Amazon EC2 resources and launch your EC2
#### - Create your Amazon EFS file system
#### - Create your mount targets in the appropriate subnets
#### - Connect your Amazon EC2 instances to the mount targets
#### - Verify the resources and protection of your AWS account

### Amazon S3 Glacier
#### - Data archiving service that is designed for security, durability, and an extremely low cost
#### - Designed to proved 11 9s of durability 
#### - Supports encryption of data in transit and at rest through SSL or TLS
#### - Low cost

### Data stored in glacier could take hours to retrieve

### Vault is a container for storing archives 

### Common use cases for Glacier
#### - Media asset archiving 
#### - Healthcare information archiving
#### - Regulatory and compliance archiving
#### - Scientific data archiving 
#### - Digital preservation 
#### - Magnetic tape replacement

## S3 storage classe

### S3 Standard 
#### - greater than or equal to three availability zones
### S3 Standard-infrequent Access (IA)
#### - retrieval fee is associated with objects
#### - Most suitable for infrequent accessed data
### S3 Intelligent-Tiering
#### - it automatically moves objects between tiers based on access
#### - Greater than or equal to availability zones
### S3 one zone-IA
#### - one availability zone 
#### - Cost less than amazon s3 standard-IA
### S3 Glacier
#### - it is not available for real-time access
#### - You must restore objects before you can access them
#### - Restoring objects can take between 1 minute and 12 hours
### S3 Glacier Deep Archive
#### - Lowest cost storage for long-term retention (7-10 years)
#### - Greater than or equal to three availability zones
#### - Retrieval time within 12 hours

# Module 8

## Amazon Relational Database 

### Organizations manage application optimization 

### Relational db works with structured data that is organized by tables records and columns

### Non-relational DB any database that does not follow the traditional relational db model

### Compatible with: MySQL, Amazon Aurora, MS SQL Server, postgreSQL, MariaDB, Oracle

### Amazon DynamoDB - Fast and flexible NoSQL database service for any scale
#### - NoSQL database tables
#### - Virtually unlimited storage
#### - Items can have differing attributes 
#### - Low-latency queries 
#### - Scalable read/write throughput

### Core components
#### - tables, items, and attributes are the core DynamoDB components
#### - DynamoDB supports two different kinds of primary keys: Partition Key and partition and sort key

### Amazon Redshift - fully managed data warehouse

### Amazon Aurora 
#### - MySQL and PostgresSQL compatible
#### - Designed for instance crash recovery

## Module 9 Could Architecture

### AWS Well-Architected Framework
#### - A guide for designing infrastructures that are secure, high-performing, resilient, efficient
#### - A consistent approach to evaluating and implementing cloud architecture
#### - A way to provide best practices that were developed through lessons learned by reviewing customer architectures 

### Cloud architects engage with decision makers to identify the business goal

### Pillars of the AWS well-architected framework
#### - Operational excellence
#### - Security
#### - Reliability
#### - Performance efficiency
#### - Cost optimization

### Operational Excellence Pillar
#### - Run and monitor systems to deliver business value, and to continually improve supporting processes and procedures

### Principles of O.E.
#### - Perform operations as code
#### - Annotate documentation
#### - Make frequent, small, reversible changes
#### - Refine operations procedures frequently
#### - Anticipate failure
#### - Learn from all operational events and failures

### Security Pillar
#### - protect information systems and assets while delivering business value through risk assessments and mitigation strategies 

### Principles of Security 
#### - implement a strong identity foundation 
#### - Enable traceability
#### - Apply security at all layers
#### - Automate security best practices
#### - Protect data in transit and at rest
#### - Keep people away from data
#### - Prepare for security events

### Reliability Pillar
#### - prevent and quickly recover from failures to meet business and customer demand

### Principles of Reliability
#### - Test recovery procedures
#### - Automatically recover from failure
#### - Scale horizontally to increase aggregate system availability 
#### - Spot guessing capacity
#### - Manage change in automation

### Performance Efficiency Pillar
#### - use IT and computing resources efficiently to meet system requirements and to maintain that efficiency as demand changes and technologies evolve

### Principles of Performance efficiency
#### - Democratize advanced technologies
#### - Go global in minutes
#### - Use serverless architectures
#### - Experiment more often
#### - Have mechanical sympathy

### Cost Optimization Pillar
#### - run systems to deliver business value at the lowest price point

### Principles of cost optimization
#### - adopt a consumption model
#### - Measure overall efficiency
#### - Stop spending money on data center operations
#### - Analyze and attribute expenditure
#### - Use managed and application-level services to reduce cost of ownership

## Reliability and availability 

### Reliability - a measure of your system’s ability to provide functionality when desired by the user

### Availability - the percentage of time a system is operating normally 

### A highly available system can withstand some measure of degradation while still remaining available 

### Factors that influence availability 
#### - fault tolerance 
#### - Scalability 
#### - Recoverability

## AWS Trusted Advisor

### - online tool that provides real-time guidance to help you provision your resources following AWS best Practices 
### - Looks at your entire AWS environment and gives you real-time recommendations in five categories 
  #### - cost optimization 
  #### - Performance
  #### - Security 
  #### - Fault tolerance
  #### - Service limits


# Module 10 Automatic Scaling and Monitoring

## Elastic Load Balancing
#### -Distributes incoming application or network traffic across multiple targets in a single Availability Zone or across multiple Availability Zones
#### - Scales your load balancers as traffic to your application changes over time.

### 3 Types of load balancers

### Application Load Balancer
#### - Load balancing of HTTP and HTTPS traffic
#### - Routes traffic to targets based on content of request
#### - Providers advanced request routing targeted at the delivery of modern application architectures, including microservices and containers
#### - Operates at the application layer (OSI model layer 7)

### Network Load Balancer
#### - Load balancing of TCP, UDP, and TLS traffic where extreme performance is required
#### - Routes traffic to targets based on IP protocol data
#### - Can handle millions of requests per second while maintaining ultra-low latencies
#### - Is optimized to handle sudden and volatile traffic patterns
#### - Operates at the transport layer (OSI model layer 4)

### Classic Load Balancer (Previous Generation)
#### - Load balancing of HTTP, HTTPS, TCP, and SSL traffic
#### - Load balancing across multiple EC2 instances
#### - Operates at both the application and transport layers

### Application load balancers and network load balancers, you register targets in target groups, and route traffic to the target groups

### Classic load balancers, you register instances with the load balancer

### Use cases
#### - High available and fault- tolerant applications
#### - Containerized applications
#### - Elasticity and scalability 
#### - Virtual private cloud (VPC)
#### - Hybrid environments 
#### - Invoke Lambda functions over HTTP(S)

### Monitoring load balancers 
#### - Amazon CloudWatch metrics: Used to verify that the system is performing as expected and creates an alarm to initiate an action if a metric goes outside an acceptable range.
#### - Access logs: Capture detailed information about requests sent to your load balancer
#### - AWS CloudTrail logs: Capture the whole, what, when, and where of API interactions in AWS services

### Amazon CloudWatch
#### - Monitors
  ##### - AWS resources
  ##### - Applications that run on AWS
#### - Collects and tracks
  ##### - Standard metrics
  ##### - Custom metrics
### - Alarms
  ##### - Send notifications to an amazon SNS topic
  ##### - Perform Amazon EC2 Auto Scaling or Amazon EC2 actions
#### - Events
  ##### - Define rules to match changes in AWS environment and route these events to one or more target functions or streams for processing

### CloudWatch is built for 
#### - DevOps engineers
#### - Developers
#### - Site reliability engineers
#### - IT managers

### CloudWatch alarms 
#### - Created based on
  ##### - Static threshold
  ##### - Anomaly detection
  ##### - Metric math expression
#### - Need to specify
  ##### - Namespace
  ##### - Metric
  ##### - Statistics
  ##### - Period
  ##### - Conditions
  ##### - Additional configuration
  #####- Actions

### Amazon EC2/Auto Scaling
#### - Helps maintain application availability 
#### - Enables you to automatically add or remove EC2 instances according to conditions that you define
#### - Detects impaired EC2 instances and unhealthy applications, and replaces the instances without your intervention
#### - Provides several scaling options - Manual, scheduled, dynamic, or on-demand, and predictive

### Auto Scaling Group: is a collection of EC2 instances that are treated as a logical grouping for the purposes of automatic scaling and management

### Launching instances is referred to as scaling out

### Terminating instances is referred to as scaling in

### AWS Auto Scaling
#### - Monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost
#### - Provides a simple, powerful user interface that enables you to build scaling plans for resources, including:
  ##### - Amazon EC2 instances and Spot Fleets
  ##### - Amazon Elastic Container Service (Amazon ECS) tasks
  ##### - Amazon DynamoDB tables and indexes
  ##### - Amazon Aurora Replicas
