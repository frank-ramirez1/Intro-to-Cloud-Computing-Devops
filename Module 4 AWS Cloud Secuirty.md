# Module 4 - AWS Cloud Security

## AWS Shared Responsibility Model
### - AWS is responsible for security of the cloud
### - Customers are responsible for securing every app and data set that they implement in the cloud
### - AWS Secures Software, hardware and networking 
### - Customer is responsible for data at rest and transit 
### - Customer should secure the firewall and passwords
## Examples of services managed by the customer
### - Amazon EC2
### - Amazon Elastic Block Store
### - Amazon Virtual Private Cloud

## Examples of services managed by AWS
### - AWS Lambda 
### - Amazon Relational Database Service
### - AWS Elastic Beanstalk
## Infrastructure as a service (IaaS)
### - Customer has more flexibility over configuration networking and storage
### - Customer is responsible for managing more aspects of the security
### - Customer configures the access controls
## Platform as a Service (PaaS)
### - Customer does not need to manage the underlying infrastructure
### - AWS handles the os, db, patching, firewall config, and disaster recovery
### - Customer can focus on managing code or data

## Software as a Service (SaaS)
### - Software is centrally hosted
### - Licensed on a subscription model or pay-as-you-go basis
### - Services are typically accessed via web browser, mobile app, or application programming interface (API)
### - Customers do not need to manage the infrastructure that supports the service

## AWS IAM

### Identity and Access Management (IAM) is a free service

### IAM Essential components 
####- IAM User: A person or application that can authenticate with an AWS account
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

### Roles do not have standard credentials

### AWS Securing a New Account

#### - While logged in as root user create an IAM user for yourself. Save access keys if needed
#### - Create an IAM  group, give it full access permissions, and add the IAM user to the group
#### - Disable and remove your account root user access keys, if they exist 
#### - Enable password policy for users
#### - Sign in with your new IAM user credentials
#### - Sign in with new IAM user 
#### - Store your account root user credentials in a secure place
### CloudTrail 
#### - tracks activity on your account
#### - Logs all API interactions

### Securing Accounts

### AWS Organizations
#### - Allows you to group multiple accounts into OUs

### Service Control Policies - offer centralized control over accounts.

## AWS Key Management Service (AWS KMS) 

### - Enables you to create and manage encryption keys
### - Enables you to control the use of encryption across AWS services and in your applications
### - Integrates with AWS CloudTrail to log all key usage

## Amazon Shield
### - Is a managed distributed denial of service (DDoS) protection service
### - Safeguards applications running on AWS
### - Provides always-on detection and automatic inline mitigations 
### - AWS Sheild Standard enabled for at no additional cost. AWS Shield Advanced is an optional paid service.
## Use it to minimize application downtime and latency

## Securing Data
### Encryption can be enabled

### By default all S3 buckets are private and protected

### AWS Config
#### - Assess, audit, and evaluate the configurations of AWS resources
#### - Use for continuous monitoring of configurations
#### - Review configuration changes
#### - View detailed configurations histories
#### - Simplify compliance auditing and security analysis
