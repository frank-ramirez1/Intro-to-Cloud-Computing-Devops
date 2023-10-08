# Module 10 Automatic Scaling and Monitoring

## Elastic Load Balancing
### -Distributes incoming application or network traffic across multiple targets in a single Availability Zone or across multiple Availability Zones
### - Scales your load balancers as traffic to your application changes over time.

## 3 Types of load balancers

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

## Amazon CloudWatch
### - Monitors
  #### - AWS resources
  #### - Applications that run on AWS
### - Collects and tracks
  #### - Standard metrics
  #### - Custom metrics
### - Alarms
  #### - Send notifications to an amazon SNS topic
  #### - Perform Amazon EC2 Auto Scaling or Amazon EC2 actions
### - Events
  #### - Define rules to match changes in AWS environment and route these events to one or more target functions or streams for processing

## CloudWatch is build for 
### - DevOps engineers
### - Developers
### - Site reliability engineers
### - IT managers

## CloudWatch alarms 
### - Created based on
  #### - Static threshold
  #### - Anomaly detection
  #### - Metric math expression
### - Need to specify
  #### - Namespace
  #### - Metric
  #### - Statistics
  #### - Period
  #### - Conditions
  #### - Additional configuration
  #### - Actions

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
