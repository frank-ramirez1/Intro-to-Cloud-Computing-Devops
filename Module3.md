AWS Global Infrastructure

AWS Region is a physical geographical location

Each region provides full redundancy and connectivity to the network

A region usually consist of two or more Availability Zones

Availability zones usually have one or more data center

Data is not replicated automatically across different regions
- This needs to be done by the client

AWS Management console can be used to enable or disable regions

Factors when selecting a region
- Data governance, legal requirements
- Proximity to customers (Latency)
- Services available within the region
- Cost (vary by Region)

Availability Zones are fully isolated partitions of the AWS infrastructure 

AWS recommends replicating data and resources across Availability Zones for resiliency

AWS data centers are designed for security

Data centers have redundant power, networking, and connectivity and is housed in a separate facility

Data centers usually have 50,000 to 80,000 physical servers

Original Design Manufacturers or ODMs design and manufacture products based on specifications from a second company

Amazon Cloudfront -  is a content delivery network used to distribute content to end user to reduce latency

AWS infrastructure features
- Elasticity and Scalability
    - Elastic infrastructure; dynamic adaption of capacity
    - Scalable infrastructure; adapts to accommodate growth
- Fault-tolerance
    - Continues operating properly in the presence of a failure
    - Built-in redundancy of components
- High availability 
    - High level of operational performance
    - Minimize downtime
    - No human intervention

AWS Services and Service Categories

AWS has 23 service categories 
- Each category contains one or more services

Most widely used services

AWS Storage services
- Amazon S3
- Amazon EBS
- Amazon EFS
- Amazon S3 Glacier

AWS Computer services
- Amazon EC2 
- Amazon EC2 Auto Scaling
- Amazon Elastic Container Service
- Amazon EC2 Container Registry
- AWS Elastic Beanstalk
- AWS Lambda
- Amazon EKS
- AWS Fargate

AWS Database services
- Amazon Relational Database Services
- Amazon Aurora
- Amazon Redshift
- Amazon DynamoDB

AWS Networking and Content delivery services
- Amazon VPC
- Amazon Load Balancing 
- Amazon CloudFront
- AWS Transit Gateway
- Amazon Route 53
- AWS Direct Connect
- AWS VPN

AWS security, identity, and compliance services
- AWS IAM
- AWS Organizations
- Amazon Cognito
- AWS Artifact
- AWS Key Management Service
- AWS Shield

AWS cost management services
- AWS Cost and Usage Report
- AWS Budgets
- AWS Cost Explorer

AWS management and governance services
- AWS Management Console
- AWS Config
- AWS CloudWatch
- AWS Auto Scaling
- AWS CLI
- AWS Trusted Advisor
- AWS Well-Architected Tool
- AWS CloudTrail
