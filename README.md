# AWS Cloud Resume Platform

This project demonstrates a serverless cloud application built using AWS services.

The platform hosts a personal resume website backed by a serverless API that tracks visitor counts and displays project information.

## Architecture

Frontend:
- S3 static website hosting
- CloudFront CDN
- Route53 DNS

Backend:
- API Gateway
- AWS Lambda
- DynamoDB

Monitoring:
- CloudWatch logs and alarms

## AWS Services Used

- Amazon S3
- Amazon CloudFront
- Amazon Route53
- AWS Certificate Manager
- AWS Lambda
- Amazon API Gateway
- Amazon DynamoDB
- AWS IAM
- Amazon CloudWatch

## Features

- Public HTTPS resume website
- Visitor counter
- Serverless backend API
- DynamoDB data storage
- Cloud monitoring and logging

## Project Phases

Phase 1
- Static site hosting
- Visitor counter API
- DynamoDB integration

Phase 2
- Terraform Infrastructure as Code
- CI/CD pipeline

Phase 3
- Security hardening and monitoring

Phase 4
- Containerized workloads (ECS/EKS)

## Author

Joseph Wilson