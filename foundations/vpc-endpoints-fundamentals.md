# AWS VPC Endpoints Fundamentals

## What VPC Endpoints Are
AWS VPC Endpoints allow resources inside a VPC to privately connect to AWS services without traversing the public internet.

## Why VPC Endpoints Matter
They improve security, reduce internet exposure, and enable private communication between cloud resources and AWS services.

---

# Core Concepts

## Gateway Endpoints
- Used for S3 and DynamoDB only  
- Modify route tables automatically  
- No hourly or data processing cost  

## Interface Endpoints
- Create Elastic Network Interfaces (ENIs) inside subnets  
- Provide private IP connectivity to AWS services  
- Powered by AWS PrivateLink  
- Have hourly and data processing costs  

## Security Groups vs. NACLs
- Security Groups are stateful  
- NACLs are stateless  
- Both provide layered network security  

## Endpoint Policies
- Control which resources can be accessed through the endpoint  
- Use JSON-based permissions  
- Can restrict access to specific S3 buckets  

## Bastion Host vs. VPC Endpoint
- Bastion Hosts provide administrative access into the VPC  
- VPC Endpoints provide private access from the VPC to AWS services  

---

# What I Practiced

- Learned the architecture and purpose of VPC Endpoints  
- Compared Gateway and Interface Endpoints  
- Reviewed how route tables interact with Gateway Endpoints  
- Studied ENI behavior for Interface Endpoints  
- Explored Security Group and NACL traffic behavior  
- Analyzed endpoint policies for restricting S3 bucket access  
- Reviewed high availability and cost considerations across Availability Zones  

---

## Why It Matters
VPC Endpoints are essential for building secure and scalable AWS architectures with private service communication.
