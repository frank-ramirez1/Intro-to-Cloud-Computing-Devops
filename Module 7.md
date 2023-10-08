# Storage

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

## Amazon Simple Storage Service (Amazon S3)

### Provides 11 9s durability

### You get fine grade control over who access the data

## Amazon Elastic File System (Amazon EFS)

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

## Amazon S3 Glacier
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

## S3 storage classes

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
