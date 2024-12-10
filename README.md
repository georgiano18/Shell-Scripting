# Shell Scripting for AWS Resource Listing

This script allows you to list various AWS resources using the AWS CLI. It supports multiple AWS services such as EC2, S3, RDS, and more.

## Features

- List EC2 instances
- List S3 buckets
- List RDS instances
- List DynamoDB tables
- List Lambda functions
- And many more...

## Requirements

- AWS CLI installed
- AWS credentials configured (`aws configure`)

## Usage

To use the script, run it with the desired AWS region and service name:

```bash
./aws_resource_list.sh <region> <service_name>
```
Example
```
./aws_resource_list.sh us-east-1 ec2
```
Supported Services:
EC2
S3
RDS
DynamoDB
Lambda
VPC
CloudFront
SNS
SQS
ECR
EKS
IAM
Route53
CloudWatch
CloudFormation
