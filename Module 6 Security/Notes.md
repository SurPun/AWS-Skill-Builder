## Lesson 38 - Module 6 Introduction

AWS Shared Responsibility Model

## Lesson 39 - Shared responsibility model

- Customers are responsible for the security of everything that they create and put in the AWS Cloud.

- AWS is responsible for security of the cloud.

Knowledge Check:

Which tasks are the responsibilities of customers? (Select TWO.)

    Patching software on Amazon EC2 instances

    Setting permissions for Amazon S3 objects

The other three response options are tasks that are the responsibility of AWS.

## Lesson 40 - User permissions and access

- AWS Identity and Access Management (AWS IAM)

- AWS IAM

  - Root user
  - Users
  - Groups
  - Policies
  - Roles

- AWS IAM Roles
  - Associated Permissions
  - Allow or deny specific actions
  - Assumed for temporary amounts of time
  - No username or password
  - Access to temporary permissions
  - AWS recources
  - Users
  - External identities
  - Applications
  - Other AWS services

## Lesson 41 - AWS Organizations

- AWS Organizations
  - A central location to manage multiple AWS accounts
  - Centralized management
  - Consolidated billing
  - Hierarchial groupings
  - AWS service and API a ctions access control
  - Service Control Policies (SCPs)
  - Organizational units (OUs)

Knowledge Check :

You are configuring service control policies (SCPs) in AWS Organizations. Which identities and resources can SCPs be applied to? (Select TWO.)

    - An individual member account

    - An organizational unit (OU)

In AWS Organizations, you can apply service control policies (SCPs) to the organization root, an individual member account, or an OU. An SCP affects all IAM users, groups, and roles within an account, including the AWS account root user.

You can apply IAM policies to IAM users, groups, or roles. You cannot apply an IAM policy to the AWS account root user.

## Lesson 42 - Compliance

- GDPR
- Health Insurance Portability and Accountability Act (HIPAA) - USA

- AWS Artifact
  is a service that provides on-demand access to AWS security and compliance reports and select online agreements. AWS Artifact consists of two main sections: AWS Artifact Agreements and AWS Artifact Reports.
- AWS Compliance

- Customer Compliance Center

Knowledge Check :

Which tasks can you complete in AWS Artifact? (Select TWO.)

- Access AWS compliance reports on-demand.

- Review, accept, and manage agreements with AWS.

The other response options are incorrect because:

    Consolidate and manage multiple AWS accounts within a central location- This task can be completed in AWS Organizations.

    Create users to enable people and applications to interact with AWS services and resources- This task can be completed in AWS Identity and Access Management (IAM).

    Set permissions for accounts by configuring service control policies (SCPs)- This task can be completed in AWS Organizations.
