# Terraform Fundamentals on AWS

## What Terraform Is

Terraform is an Infrastructure as Code (IaC) tool used to define, provision, and manage cloud infrastructure in a declarative way.

## Why Terraform Matters

It allows infrastructure to be versioned, reusable, and automated, reducing manual cloud configuration and improving scalability and consistency.

---

# Core Concepts

## Providers

- Connect Terraform to cloud platforms like AWS
- Define where resources will be created

## Resources

- Infrastructure components such as EC2, VPC, and Security Groups
- Defined declaratively in configuration files

## State

- `terraform.tfstate` tracks real infrastructure
- Maps code to actual AWS resources

## Plan & Apply

- `terraform plan` → previews changes before execution
- `terraform apply` → executes and creates infrastructure

---

# What I Practiced

- Installed and configured Terraform on Linux
- Verified installation using `terraform -v`
- Initialized project using `terraform init`
- Planned infrastructure changes with `terraform plan`
- Applied configuration using `terraform apply`
- Deployed first EC2 instance using AWS provider
- Used tags to identify resources (e.g., Name = "test2")
- Learned to reference existing AWS resources using data sources
- Understood the role of variables for reusable configurations

---

## Key Takeaways

- Terraform uses a declarative approach, not scripting
- State management is critical for tracking infrastructure
- Plan → Apply workflow ensures safe infrastructure changes
- Code structure determines scalability in real projects

---

## Why It Matters

Terraform enables scalable, repeatable, and automated cloud infrastructure management, which is essential for modern DevOps and Cloud Engineering roles.
