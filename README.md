# Serverless Image Processing Pipeline using AWS

## Project Overview
This project automatically processes images uploaded into Amazon S3 using AWS Lambda and Rekognition. After processing, SNS sends email notifications containing detected labels.

## AWS Services Used
- Amazon S3
- AWS Lambda
- AWS Rekognition
- Amazon SNS
- AWS IAM
- CloudWatch

## Workflow
S3 Bucket → Lambda → Rekognition → SNS Email Notification

## Features
- Automatic image processing
- Event-driven architecture
- AI label detection
- Email notifications
- Fully serverless system

## Technologies
- Python
- Boto3
- AWS Cloud

## Example Output
Detected Labels:
Dog, Animal, Pet

## Author
Abhishek