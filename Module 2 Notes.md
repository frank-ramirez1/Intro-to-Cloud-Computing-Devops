# Module 2 - Cloud Economics and Billing

## Fundamentals and Pricing

### Three fundamental cost of AWS
#### - Compute
#####  - Charged per hour/second
#####  - Varies by instance type
#### - Storage
#####  - Charged typically per GB
#### - Data Transfer
##### - Outbound is aggregated and charged
##### - Inbound has no charge (with some exceptions)
##### - Charged typically per GB

### Pay for what you use only

### There a volume based discounts

### Benefit from growing economies of scale

### Some services are no additional charge
#### - Amazon VPC
#### - Elastic Beanstalk
#### - Auto Scaling
#### - AWS CloudFormation
#### - AWS identity and Access Management (IAM)

### Total Cost of Ownership 
####  - Financial estimate to help identify direct and indirect cost of a system

### AWS Pricing Calculator helps with 
####  - Estimate monthly cost
####  - Identify opportunities to reduce monthly cost
####  - Model your solutions before building


## AWS Organizations

### Allows consolidation of multiple accounts 

### AWS Organizations Enables organizations to have:
####  - policy-based account management
####  - Group based account management 
####  - Application programming interfaces (APIs) that automate account management 
####  - Consolidated billing

### AWS Organizations does not replace using AWS Identity and Access Management 

### IAM policies allow and denies access to AWS services for users, groups and roles

### Service control policies (SCPs) enable you to allow or deny access to AWS services for individual or group accounts in an OU

### Steps to create to use AWS Organizations
####  1. create organization
####  2. Create organizational units
####  3. Create service control policies
####  4. Test restrictions

### It can be managed by different interfaces
####  - AWS Mangement Console
####  - AWS CLI tools
####  - Software development kits (SDKs)
####  - HTTPS query application programming interfaces (API)

## AWS Billing & Cost Management

### - Service to pay bills and monitor usage
### - AWS Billing Dashboard provides high-level of how cost are tending

### There are several other cost management tools
####  - AWS Budget
####  - AWS Cost and Usage Report
####  - AWS Cost Explorer


## Technical Support Models

### AWS Support
####  - Proactive guidance:
#####   - Technical Account Manager (TAM)
#####   - Primary point of contact 
#####   - Provide guidance, architectual review
####  - Best practices:
#####    - AWS Trusted Advisor
#####    - Automated service that acts as a customized cloud expert, online resource to help with productivity and lowering cost.
####  - Account assistance:
#####    - AWS Support Concierge
######   - Addresses non-technical, billing and account level inquiries

### Support plans
####  - Basic Support: Resource Center access, Service Health Dashboard, product FAQs, discussion forums, and support for health checks
####  - Developer Support: Support for early development on AWS
####  - Business Support: Customers that run production workloads
####  - Enterprise Support: Customer that run business and mission-critical workloads.
