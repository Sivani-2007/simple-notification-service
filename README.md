# Simple Notification Service

## Project Description
This is a mini project demonstrating how to build a notification system using AWS services.

## AWS Services Used
- Amazon EC2
- Amazon CloudWatch
- Amazon SNS
- Amazon SQS

## Workflow
1. EC2 instance is monitored using CloudWatch.
2. CloudWatch triggers an alarm when a condition is met.
3. The alarm sends a notification through SNS.
4. The message is delivered to subscribers and stored in SQS.

## Conclusion
This project shows how AWS cloud services can work together to create a scalable and reliable notification system.
