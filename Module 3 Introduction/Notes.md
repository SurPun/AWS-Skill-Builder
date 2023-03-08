## Lesson 15 - Module 3 Introduction

- AWS Global Infrastructure

  To understand the AWS global infrastructure, consider the coffee shop. If an event such as a parade, flood, or power outage impacts one location, customers can still get their coffee by visiting a different location only a few blocks away.

  This is similar to how the AWS global infrastructure works.

## Lesson 16 - AWS global infrastructure

- Selecting a Region

  - Compliance with data governance and legal requirements
  - Proximity to your customers
  - Available services within a Region
  - Pricing

- Availability Zones

  -

- Knowledge check

  - Which statement best describes an Availability Zone?

    - The correct response option is A single data center or group of data centers within a Region.

    The other response options are incorrect because:

    A Region is a geographical area that contains AWS resources.
    An edge location is a data center that an AWS service uses to perform service-specific operations. Edge locations are examined in the next section of this module.
    AWS Outposts is a service that you can use to run AWS infrastructure, services, and tools in your own on-premises data center in a hybrid approach. AWS Outposts is explored later in this module.

## Lesson 17 - Edge Locations

- Content Delivery Network (CDN) - Amazon Cloudfront
- Amazon Route 53 - DNS
- AWS Outposts

- Regions are geographically isolated areas.
- Regions contain Availability Zones.
- Edge locations run Amazon CloudFront.
  - An edge location is a site that Amazon CloudFront uses to store cached copies of your content closer to your customers for faster delivery.

## Lesson 18 - How to provision AWS resources

- Ways to interact with AWS services

  - AWS Management Console
  - AWS CLI
  - Software Development Kits SDKs

- AWS Elastic Beanstalk

  - With AWS Elastic Beanstalk, you provide code and configuration settings, and Elastic Beanstalk deploys the resources necessary to perform the following tasks:

    - Adjust capacity
    - Load balancing
    - Automatic scaling
    - Application health monitoring

- AWS CloudFormation

  - With AWS CloudFormation, you can treat your infrastructure as code. This means that you can build an environment by writing lines of code instead of using the AWS Management Console to individually provision resources.

  - AWS CloudFormation provisions your resources in a safe, repeatable manner, enabling you to frequently build your infrastructure and applications without having to perform manual actions. It determines the right operations to perform when managing your stack and rolls back changes automatically if it detects errors

## Lesson 19 - Module 3 Summary
