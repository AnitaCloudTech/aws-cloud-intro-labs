# aws-cloud-intro-labs
# AWS Cloud Intro Labs  This repository documents all labs completed in the **“Introduction to AWS Cloud: Builder Labs Learning Plan”**. The goal is to showcase hands-on skills in AWS cloud services.
## Contents

- **VPC** – Create Virtual Private Cloud, Internet Gateway, subnets, and routing.
- **EC2** – Launch, resize, manage, and monitor EC2 instances.
- **Lambda** – Create and deploy event-driven Lambda functions.
- **DynamoDB** – Create, query, update, and delete tables.
- **API Gateway** – Build a simple FAQ microservice invoking a Lambda function.
- **S3** – Manage buckets and objects.
- **IAM** – Manage users, groups, and policies.
- **Audit** – Perform basic AWS audits using CloudTrail and CloudWatch.
- **KMS** – Manage encryption keys and encrypt data.
- **CloudFront** – Create distributions to deliver content from S3.

# Amazon CloudFront Lab

This lab introduces AWS CloudFront for content delivery.

## Objectives

- Create a CloudFront distribution
- Serve content from an S3 bucket
- Understand caching and edge locations

## Steps

1. Ensure you have a public S3 bucket with content
2. Open CloudFront in AWS Console
3. Create a new Web distribution
4. Select the S3 bucket as origin
5. Configure caching and behaviors
6. Deploy and test using the CloudFront domain

## Author

Anita Mijatović 

## License

[MIT](LICENSE)
