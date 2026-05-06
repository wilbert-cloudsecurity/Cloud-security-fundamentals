# AWS CloudTrail Fundamentals

## What CloudTrail Is

AWS CloudTrail is a service that records account activity and API calls, providing visibility into actions performed within AWS.

## Why CloudTrail Matters

It is essential for auditing, security monitoring, and compliance by tracking who did what, when, and from where in the AWS environment.

---

# Core Concepts

## Trails

- Record AWS API activity across services
- Can be created via Console, CLI, or Infrastructure as Code
- Deliver logs to S3 buckets

## Event History

- View recent account activity directly in AWS
- Useful for quick inspection and troubleshooting

## S3 Logging

- CloudTrail stores logs in S3
- Requires proper bucket policies to allow log delivery
- Prefixes help organize logs and avoid clutter

---

# What I Practiced

- Learned CloudTrail core concepts and use cases
- Explored Event History in the AWS Console
- Created a trail using:
    - AWS Management Console
    - AWS CLI
    - Terraform (Infrastructure as Code)
- Configured all trails to deliver logs to a single S3 bucket
- Updated bucket policy to allow multiple trails to write logs
- Used prefixes to organize logs and prevent overlap

---

# Key Considerations

- S3 bucket must exist before creating trails via CLI or Terraform
- Bucket policies may need adjustment when multiple trails write to the same bucket
- Proper use of prefixes improves log organization and scalability

---

## Why It Matters

CloudTrail is critical for auditing, incident investigation, and maintaining visibility over cloud activity in secure environments.
