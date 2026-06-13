# Serverless REST API Deployment using AWS Lambda, API Gateway, and Terraform

## What This Project Covers

This project focuses on understanding how APIs work in AWS by building and deploying a simple serverless REST API using AWS Lambda, API Gateway, and Terraform.

The goal was to learn API fundamentals through hands-on practice instead of only studying theory.

- --

## Why It Matters

APIs are a core part of modern cloud applications. Understanding how requests are received, processed, and connected to backend services is essential for Cloud Engineering and Cloud Security roles.

This project also introduces Infrastructure as Code (IaC) principles by automating deployment with Terraform.

- --

# Core Concepts

## API Gateway

- **HTTP Methods** → Define how clients interact with the API (GET, POST, etc.)
- **Routes and Endpoints** → Expose functionality through public URLs
- **Service Integration** → Connect API Gateway with backend services such as Lambda

## AWS Lambda

- **Serverless Compute** → Run code without managing servers
- **Event-Driven Execution** → Functions execute in response to API requests
- **Scalability** → Automatically scales based on incoming traffic

## Terraform

- **Infrastructure as Code (IaC)** → Provision AWS resources declaratively
- **Resource Management** → Create and manage Lambda functions and API Gateway resources
- **Deployment Automation** → Standardize and reproduce infrastructure consistently

## REST APIs

- **Client-Server Communication** → APIs allow systems to exchange data through HTTP requests
- **HTTP Methods** → Requests are processed using methods such as GET and POST
- **JSON Responses** → APIs commonly return structured JSON data
- --

# What I Practiced

- Learned the general architecture and purpose of REST APIs
- Created an AWS Lambda function
- Created an API Gateway REST API
- Configured an HTTP method and integrated it with Lambda
- Connected AWS services to process API requests
- Deployed the API and validated functionality
- Used Terraform to provision and manage infrastructure resources
- --

# Project Structure

- `main.tf` → API Gateway and Lambda infrastructure
- `variables.tf` → Reusable Terraform variables
- `outputs.tf` → Deployment outputs and API endpoint information
- `lambda_function.py` → Lambda function code
- `terraform.tfvars` → Environment-specific values
- --

## Key Takeaways

- APIs are fundamental for communication between cloud services and applications
- Serverless architecture simplifies deployment and scaling
- API Gateway and Lambda integrate seamlessly for lightweight backend services
- Terraform enables repeatable and automated infrastructure deployment
- Hands-on implementation improves understanding of cloud architecture concepts
