# AWS-Skill-Builder

Documentation of Learnings...

## What is Cloud Computing Quiz

    1. You ONLY want to manage Applications and Data. Which type of Cloud Computing model should you use?

        - (Platform as a Service (PaaS)) In the Platform as a Service model, you only manage the data and the applications.

    2. What is the pricing model of Cloud Computing?

        - (Pay-as-you-go pricing) In Cloud Computing, you are only charged for what you use.

    3. Which Global Infrastructure identity is composed of one or more discrete data centers with redundant power, networking, and connectivity, and are used to deploy infrastructure?

        - This is the definition of Availability Zones.

    4. Which of the following is NOT one of the Five Characteristics of Cloud Computing?

        - Dedicated Support Agent to help you deploy applications.

    5. Which are the 3 pricing fundamentals of the AWS Cloud?

        - Compute, Storage, and data transfer out of the AWS Cloud are the 3 pricing fundamentals of the AWS Cloud.

    6. Which of the following options is NOT a point of consideration when choosing an AWS Region?

        - (Capacity Availability) Capacity is unlimited in the cloud, you do not need to worry about it. The 4 points of considerations when choosing an AWS Region are: compliance with data governance and legal requirements, proximity to customers, available services and features within a Region, and pricing.

    7. Which of the following is NOT an advantage of Cloud Computing?

        - (Train your employees less) You must train your employees more so they can use the cloud effectively.

    8. AWS Regions are composed of?

        - Three or more Availability Zones

    9. Which of the following services has a global scope?

        - IAM

    10. Which of the following is the definition of Cloud Computing?

        - On-demand availability of computer system resources, especially data storage (cloud storage) and computing power, without direct active management by the user.

    11. What defines the distribution of responsibilities for security in the AWS Cloud?

        - The Shared Responsibility Model defines who is responsible for what in the AWS Cloud.

    12. A company would like to benefit from the advantages of the Public Cloud but would like to keep sensitive assets in its own infrastructure. Which deployment model should the company use?

        - (Hybird Cloud) Using a Hybrid Cloud deployment model allows you to benefit from the flexibility, scalability and on-demand storage access while keeping security and performance of your own infrastructure.

    13. What is NOT authorized to do on AWS according to the AWS Acceptable Use Policy?

        - (Run analytics on stolen content) You can run analytics on AWS, but you cannot run analytics on fraudulent content. Refer to the AWS Acceptable Use Policy to see what is not authorized to do on AWS.

## IAM

    1. What is a proper definition of IAM Roles?

        - An IAM entity that defines a set of permissions for making AWS service requests, that will be used by AWS services.

        Some AWS service will need to perform actions on your behalf. To do so, you assign permissions to AWS services with IAM Roles.

    2. Which of the following is an IAM Security Tool?

        - IAM Credentials Report

        IAM Credentials report lists all your account's users and the status of their various credentials. The other IAM Security Tool is IAM Access Advisor. It shows the service permissions granted to a user and when those services were last accessed.

    3. Which answer is INCORRECT regarding IAM Users?

        - IAM Users access AWS with the root account credentials.

    4. Which of the following is an IAM best practice?

        - Dont use the root user account.

    5. What are IAM Policies?

        - JSON documents to define Users, Groups or Roles' permissions

    6. Under the shared responsibility model, what is the customer responsible for in IAM?

        - Assigning users proper IAM Policies.

    7. Which of the following statements is TRUE?

        - The AWS CLI can interact with AWS using commands in your command-line shell, while the AWS SDK can interact with aWS programmatically.

    8. Which principle should you apply regarding IAM Permissions?

        - Grant least privilege.

    9. What should you do to increase your root account security?

        - Enable Multi-Factor Authentication (MFA).

## EC2

    1. Which EC2 Purchasing Option can provide the biggest discount, but is not suitable for critical jobs or databases?

        - Spot Instances

    2. Which network security tool can you use to control traffic in and out of EC2 Instances?

        - Security Groups

    3. Under the Shared Responsibility Model, who is responsible for operating-system patches and updates on EC2 Instances?

        - The customer

    4. How long can you reserve an EC2 Reserved Instance?

        - 1 or 3 Year.

    5. A company would like to deploy a high-performance computing (HPC) application on EC2. Which EC2 instance type should it choose?

        - Compute Optimized

    6. Which of the following is NOT an EC2 Instance Purchasing Option?

        - Connect Instances

    7. Which EC2 Purchasing Option should you use for an application you plan on running on a server continuously for 1 year?

        - Reserved Instances

## EC2 Instance Storage

    1. Which EC2 Storage would you use to create a shared network file system for your EC2 Instances?

        - (EFS) Amazon EFS is a fully managed service that makes it easy to set up, scale, and cost-optimize file storage in the Amazon Cloud.

    2. Which service can be used to automate image management processes?

        - (EC2 Image Builder) EC2 Image Builder is an automated pipeline for the creation, maintenance, validation, sharing, and deployment of Linux or Windows images for use on AWS and on-premises.

    3. Which of the following is a fully managed native Microsoft Windows file system?

        - (FSx) Amazon FSx makes it easy and cost effective to launch and run popular file systems that are fully managed by AWS. It comes in two offerings: FSx for Windows File Server (used for business applications), and FSx for Lustre (used for high-performance computing).

    4. What are AMIs NOT used for?

        - Add your own IP addresses

    5. EBS Volumes CANNOT be attached to multiple EC2 instances at a time.

        - (TRUE) EBS Volumes can be attached to only one EC2 Instance at a time, but EC2 Instances can have multiple EBS Volumes attached to them.

    6. An EBS Volume is a network drive you can attach to your instances while they run, so your instances' data persist even after their termination.

        - (True) EBS Volumes allows instances' data to persist even after their termination.

    7. Which statement is CORRECT regarding EC2 Instance Store?

        - It has better I/O performance, but the data is lost if the EC2 instance is terminated.

    8. What is an EBS Snapshot?

        - A backup of your EBS Volume at a point in time.

    9. Where can you find a third party's AMI so you can use it to launch your EC2 Instance?

        - AWS Marketplace AMIs

    10. What is an EBS Volume tied to?

        - An availability zone.
