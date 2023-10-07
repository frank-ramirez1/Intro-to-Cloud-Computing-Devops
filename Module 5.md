# Module 5 Networking and Content Delivery 

## Networking Basics

### Networking requires a router or a switch

### Each machine has a unique I.P Address

### 32 bit address is a IPV4 address

### 128 bit address is an IPV6 Address

### Amazon VPC
#### - Enables you to provision a logically isolated section of the AWS Cloud where you can launch AWS resource in a virtual network that you define
#### - Gives you control over your virtual networking resources
  #####  - Selection of IP address range
  #####  - Creation of subnets
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

## VPC security

### Security group acts as a virtual firewall inbound and outbound 
#### - Security groups have rules to manage instance traffic
#### - Default security groups are sealed shut to inbound traffic. We need to define rules
#### - Security groups are stateful. The outbound traffic is always allowed 
### Network ACLs
#### - A network ACL has separate inbound and outbound rules, and each rule can either allow or deny traffic
#### - Default network ACLs allow all inbound and outbound IPv4 traffic 
#### - Network ACLs are stateless

### Amazon Route 53
#### - gives you the ability to register a domain name
#### - Is a highly available and scalable domain name system (DNS) web service
#### - Is used to route end users to internet applications by translating names into numeric IP addresses that computers use to connect to each other
#### - Is fully compliant with IPv4 and IPv6
#### - Connects user request to infrastructure running in AWS and also outside of AWS 
#### - Is used to check the health of your resources
#### - Features traffic flow
#### - Enables you to register domain names

### Supported Routing
#### - Simple routing: use in single-server environments 
#### - Weighted routing: assign weights to resource record sets to specify the frequency 
#### - Latency routing: help improve your global applications
#### - Geolocation routing: route traffic based on location of your users
#### - Geoproximity routing: route traffic based on location of your resources
#### - Failover routing: fail over to a backup site if your primary site becomes unreachable 
#### - Multi value answer routing: respond to dns queries with up to eight healthy records selected at random

### Amazon Router 53 DNS failover
#### - improve the availability of your applications that run on AWS by:
  ##### - Configure backup and failover scenarios for your own applications
  ##### - Enabling high available multi-region architectures on AWS 
  ##### - Creating health check

#### Amazon CloudFront
##### - fast, global, and secure content delivery service
##### - Global network of edge locations and regional edge caches
##### - Self-service model
##### - Pay-as-you-go pricing 

### Edge locations - network of data centers that CLoudFront uses to serve popular content quickly to customers

### Regional edge cache - CloudFront locations that caches content that is not popular enough tot stay at an edge location. It is located between the origin server and the global edge location


