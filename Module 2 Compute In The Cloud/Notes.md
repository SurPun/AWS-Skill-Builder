# Notes

- IOPS:

  In computing, the term input/output operations per second (IOPS) is a metric that measures the performance of a storage device. It indicates how many different input or output operations a device can perform in one second. Storage optimized instances are designed to deliver tens of thousands of low-latency, random IOPS to applications.

- Payload:

  Data contained within a message.

- Amazon SQS queues:

  Where messages are placed until they are processed.

- Amazon SNS topic:

  A channel for messages to be delivered

## Lesson 6 - Introduction

- Using EC2 for Compute is highly flexible, cost effective and quick

## Lesson 7 - Amazon EC2 instance types

- Amazon EC2 instance families:
  - General purpose
    - Balanced resources
    - Diverse workloads
    - Web servers
    - Code repositories
  - Compute optimized
    - Compute intensive tasks
    - Gaming servers
    - High performance computing (HPC)
    - Scientific modeling
  - Memory optimized
    - Memory instensive tasks
  - Accelerated computing
    - Floating point number calculations
    - Graphics processing
    - Data pattern matching
    - Utilize hardware accelerators
  - Storage optimized
    - High performance for locally stored data

## Lesson 8 - Amazon EC2 pricing

- Amazon EC2 purchase options
  - On-Demand
  - Savings Plans
  - Reserved Instances
  - Spot Instances
  - Dedicated Hosts

## Lesson 9 - Scaling Amazon EC2

- Amazon EC2 Auto Scaling:

  By adding Amazon EC2 Auto Scaling to an application, you can add new instances to the application when necessary and terminate them when no longer needed.

## Lesson 10 - Directing traffic with Elastic Load Balancing

- Elastic Load Balancing:

  Is the AWS service that automatically distributes incoming application traffic across multiple resources, such as Amazon EC2 instances.

## Lesson 11 - Messaging and queuing

- Amazon SQS

  - Send messages
  - Store messages
  - Recieve messages
  - Between software components
  - At any volume

## Lesson 12 - Additional compute services

- Serverless: You cannot see or access the underlying infrastructure

---

Container Orchestration tools - Docker - Container is a package for your code.

- Amazon Elastic Container Service (Amazon ECS)
- Amazon Elastic Kubernetes Service (Amazon EKS)

---

- AWS Fargate (Serverless)

---

Compute services:

If you want to...

- Host traditional applications
- Full access to the OS
  ...Use Amazon EC2

---

- Host short running functions
- Service-oriented applications
- Event driven applications
- No provisioning or managing servers
  ... Use Serverless AWS Lambda

---

- Run Docker container-based workloads on AWS
- Amazon ECS or Amazon EKS
  ...Option 1 Amazon EC2 that you manage
  ...Option 2 AWS Fargate managed for you

## Lesson 13 - Module 2 summary

- Cloud computing:

  - The on-demand delivery of IT resources over the internet with pay-as-you-go pricing

- Amazon Elastic Compute Cloud (Amazon EC2:

  - EC2 instance families:

    - General purpose
    - Compute optimized
    - Memory optimized
    - Accelerated Computing
    - Storage optimized

  - Can scale EC2 instance vertically by resizing the instance or horizontally by adding more instance.

    - Amazon EC2 Auto Scaling: Automated horizontal scaling
    - Elastic load Balancing (ELB) - distributes oncoming traffic to scaled instances.

  - Amazon EC2 billing options

    - On-Demand
    - Spot Instances
    - Reserved Instances
    - Savings Plans

- Amazon Simple Queue Service (Amazon SQS):

  - This service allows you to decouple system components.
  - Messages remain in the queue until they are either consumed or deleted.

- Amazon Simple Notification Service (Amazon SNS):

  - Used for sending messages like emails, text messages, push notifications or even HTTP requests.
  - Once the message is published, it is sent to all of these subscribers.

- Container Orchestration tools:

  - Amazon Elastic Container Service (Amazon ECS)

  - Amazon Elastic Kubernetes Service (Amazon EKS)

- AWS Fargate

  - Run your containers on top of a serverless compute platform.

- AWS Lambda

  - Allows you to upload your code and configure it to run bvased on triggers.

  - Only get charged for when the code is actually running.
