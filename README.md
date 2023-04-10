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

## ELB & ASG

    1. What is the main purpose of High Availability in the Cloud?

        - Application thriving even in case of a disaster.

    2. Which AWS offered Load Balancer should you use to handle hundreds of thousands of connections with low latency?

        - Network Load Balancer

    3. Changing an EC2 Instance Type from a t3a.medium to a t3a.2xlarge is an example of?

        - Vertical scaling

    4. What can you use to handle quickly and automatically the changing load on your websites and applications by adding compute resources?

        - An Auto Scaling Group

    5. Which of the following statements is INCORRECT regarding Auto Scaling Groups?

        - Automatically changing the EC2 Instances Types

    6. Which Load Balancer is best suited for HTTP/HTTPS load balancing traffic?

        - Application Load Balancer

    7. Which of the following is NOT an Auto Scaling Strategy?

        - (Active Scaling) This is not a scaling strategy. Auto Scaling Strategies include: Manual Scaling, Dynamic Scaling (Simple/Step Scaling, Target Tracking Scaling, Scheduled Scaling), and Predictive Scaling.

    8. Which AWS service offers easy horizontal scaling of compute capacity?

        - ASG

    9. Which of the following statements is NOT a feature of Load Balancers?

        - Back-end autoscaling

## S3

    1. Which S3 Storage Class is the most cost-effective for archiving data with no retrieval time requirement?

        - (Amazon Glacier Deep Archive) is the most cost-effective option if you want to archive data and do not have a retrieval time requirement. You can retrieve data in 12 or 48 hours.

    2. What hybrid AWS service is used to allow on-premises servers to seamlessly use the AWS Cloud at the storage layer?

        - (AWS Storage Gateway) is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage.

    3. Which of the following services is a petabyte-scale data moving service (as a fleet) in or out of AWS with computing capabilities?

        - Snowball Edge

    4. Which of the following is an exabytes-scale data moving service in or out of AWS?

        - Snowmobile

    5. What are Objects NOT composed of?

        - Access Keys

    6. Where are objects stored in Amazon S3?

        - Buckets

    7. A research team deployed in a location with low-internet connection would like to move 5 TBs of data to the Cloud. Which service can it use?

        - Snowcone

    8. What can you use to define actions to move S3 objects between different storage classes?

        - Lifecycle Rules

    9. A non-profit organization needs to regularly transfer petabytes of data to the cloud and to have access to local computing capacity. Which service can help with this task?

        - Snowball Edge Storage Optimized

    10. Which S3 Storage Class is suitable for less frequently accessed data, but with rapid access when needed, while keeping a high durability and allowing an Availability Zone failure?

        - Amazon S3 Standard-Infrequent Access

## Databases & Analytics

    1. You want to create a decentralized blockchain on AWS. Which AWS service would you use?

        - Managed Blockchain

    2. Which AWS database is a data warehouse?

        - Redshift

    3. Which AWS service is always serverless and has SQL capabilities?

        - Athena

    4. You would like to use a serverless service to prepare data so it can be loaded for analytics. Which service would you use?

        - (AWS Glue) is a fully managed extract, transform, and load (ETL) service that makes it easy for customers to prepare and load their data for analytics.


    5. Which relational database is a proprietary technology from AWS and is cloud-optimized?

        - Aurora

    6. You would like to migrate databases to AWS while still being able to use the database during the migration. What service allows you to do this?

        - Database Migration Service (DMS)

    7. How can you create Hadoop clusters to analyze and process a vast amount of data?

        - Amazon EMR

    8. Which in-memory AWS database can you use to reduce the load off databases and has high performance, low latency?

        - ElastiCache

    9. What is the name of a central repository to store structural and operational metadata for data assets in AWS Glue?

        - Glue Data Catalog

    10. Which of the following databases is a managed service with SQL capability suited for Online Transaction Processing (OLTP)?

        - RDS

    11. Which AWS service is an immutable ledger database?

        - QLDB

    12. You would like to set up a NoSQL database that can scale with no downtime and can handle millions of requests per second. Which AWS database is best suited for this work?

        - DynamoDB

    13. Which AWS service can create complex graphs for fraud detection?

        - Neptune

    14. Which AWS serverless service can use machine learning-powered business intelligence to create interactive dashboards such as business analytics?

        - QuickSight

    15. A company would like to set up a fully managed MongoDB database. Which AWS database is best-suited for this task?

        - DocumentDB

    16. Which exclusive DynamoDB feature is an in-memory cache that can improve your performance up to 10x?

        - DynamoDB Accelerator

    17. RDS Multi-AZ deployments’ main purpose is high availability, while RDS Read replicas’ main purpose is scalability.

        - (TRUE) DS Multi-AZ deployments’ main purpose is high availability, and RDS Read replicas’ main purpose is scalability. Moreover, Multi-Region deployments’ main purpose is disaster recovery and local performance.

## Other Compute Services: ECS, Lambda, Batch, LightSail

    1. How do you get charged in AWS Lambda?

        - Per call and per duration

    2. You would like to launch Docker containers in AWS without worrying about provisioning or managing any infrastructure. The Docker containers will be used to host a heavy workloads to serve different types of requests. Some requests may need up to 30 minutes to be completed. Which AWS service should you use to run Docker containers in a Serverless way and satisfy the requirements?

        - Fargate

    3. A complete cloud beginner would like to create a simple application with predictable pricing. What service should this person use?

        - LightSail

    4. What is the name of the software development platform that allows you to run applications the same way, regardless of where they are run?

        - Docker

    5. How would you best describe "event-driven" in AWS Lambda?

        - Happens when needed

    6. Which AWS service allows you to launch Docker containers on AWS, but requires you to provision and maintain the infrastructure?

        - ECS

    7. Which of the following statements is INCORRECT regarding the definition of the term "serverless"?

        - There are no servers

    8. Which of the following statements is NOT a feature of AWS Lambda?

        - Definition of a minimum and a maximum of EC2 Instances running

    9. A company needs to run thousands of jobs but would like to NOT manage the compute resources. What service can it use?

        - Batch

    10. Where should you store your private Docker images so they can be run by ECS or Fargate?

        - Elastic Container Registry

    11. Which AWS serverless service can be used by developers to create APIs?

        - API Gateway

## Deployments & Managing Infrastructure at Scale

    1. CodeStar can be used to monitor and check the health of an environment.

        - False

    2. Which AWS managed service allows to automate software deployments to a hybrid mix of EC2 Instances and On-Premises servers?

        - CodeDeploy

    3. A developer team would like to collaborate on code with versioning support. Which AWS service can help the developers?

        - CodeCommit

    4. You need a unified user interface that gives you visibility, control, and patching capabilities for your EC2 Instances on AWS, as well as for servers running in your on-premises data centers. Which service should you use?

        - Systems Manager

    5. You need to use Chef or Puppet. Which AWS service should you use?

        - OpsWorks

    6. A developer would like to deploy infrastructure on AWS but only knows Python. Which AWS service can assist him?

        - CDK

    7. Which of the following allows you to deploy any AWS Infrastructure as a Code?

        - CloudFormation

    8. A new startup would like an online integrated development environment (IDE) to write, run, and debug code. Which AWS service can help with this task?

        - Cloud9

    9. Which service is referred to as a Platform as a Service (PaaS)?

        - Elastic BeanSTALK

    10. What is called the declaration of the AWS resources that make up a stack?

        - CloudFormation Templates

    11. Which of the following services can a developer use to store code dependencies?

        - Cloud Artifact

    12. CodeStar can orchestrate the different steps to have code automatically pushed to production, while CodePipeline is a unified UI to easily manage software development activities in one place.

        - False

    13. Which serverless service can be used to build code and run tests?

        - CodeBuild

    14. CloudFormation and Elastic Beanstalk are free of use.

        - True

## Leveraging the AWS Global Infrastructure

    1. Which Route 53 Routing Policies would you use to route traffic to multiple resources in proportions that you specify?

        - Weighted Routing Policy

    2. Which service is optimized to deploy ultra-low latency applications to 5G devices?

        - Wavelength

    3. You need to enable fast, easy, and secure transfers of files over long distances on S3. Which service would you use?

        - S3 Transfer Acceleration

    4. What does AWS CloudFront use to improve read performance?

        - Caching Content in Edge Locations

    5. Which service can be used to run AWS infrastructure and services on-premises for a hybrid cloud architecture?

        - Outposts

    6. Which of the following statements is NOT a reason for a global application?

        - Scale elastically on demand

    7. Which features are available with Route 53?

        - Domain Registration, DNS, Health Checks, Routing Policy

    8. With which services does CloudFront integrate to protect against web attacks?

        - WAF & Shield

## Cloud Integrations

    1. A company using Apache ActiveMQ is migrating to the cloud. Which AWS service can it use to easily set up and operate its message brokers in the cloud?

        - MQ

    2. Which service is a fully managed pub/sub messaging service that makes it easy to set up, operate, and send notifications from the cloud, using a push-based system?

        - Simple Notification Service (SNS)

    3. You can use Kinesis to perform real-time analysis from video streams.

        - True

    4. Which principle is mainly applied when using Amazon SQS or Amazon SNS?

        - Decouple your applications

    5. Which service allows you to send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available, using a pull-based system?

        - Simple Queue Service (SQS)

## Cloud Monitoring

    1. Which CloudWatch feature would you use to trigger notifications when a metric reaches a threshold you specify?

        - CloudWatch Alarms

    2. Which AWS service helps developers analyze and debug production as well as distributed applications?

        - X-Ray

    3. Which AWS service provides alerts and remediation guidance when AWS is experiencing events that may impact you?

        - Personal Health Dashboard

    4. You need to set up metrics monitoring for every service in AWS. Which service would you use?

        - CloudWatch

    5. Which service allows you to inspect, audit, and record events and API calls made within your AWS account?

        - CloudTrail

    6. Which AWS service automatically analyzes code and provides performance recommendations?

        - CodeGuru

    7. How would you describe Amazon CloudWatch Logs?

        - A single, highly scalable service that centralizes the logs from all your systems, applications, and AWS services that you use.

    8. If a resource is deleted in AWS, which service should you use to investigate first?

        - CloudTrail

## VPC & Networking

    1. Your private subnets need to connect to the Internet while still remaining private. Which AWS-managed VPC component allows you to do this?

        - NAT Gateway

    2. A public subnet is accessible from the Internet while a private subnet is not accessible from the Internet.

        - Yes

    3. Which type of firewall has both ALLOW and DENY rules and operates at the subnet level?

        - Network Access Control List (NACL)

    4. You would like to connect hundreds of VPCs and your on-premises data centers together. Which AWS service allows you to do link all these together efficiently?

        - Transit Gateway

    5. A company needs two VPCs to communicate with each other. What can they use?

        - VPC Peering

    6. You need a logically isolated section of AWS, where you can launch AWS resources in a private network that you define. What should you use?

        - A VPC

    7. A company needs to have a private, secure, and fast connection between its on-premises data centers and the AWS Cloud. Which connection should they use?

        - AWS Direct Connect

    8. Your VPC needs to connect with the Internet. Which VPC component can help?

        - Internet Gateway

## Security & Compliance

    1. Data sitting on an RDS instance would be referred to as?

        - Data at rest

    2. According to the Shared Responsibility Model, who is responsible for firewall and network configuration for EC2 Instances?

        - The Customer

    3. Which of the following services can you use to discover and protect your sensitive data in AWS?

        - Macie

    4. Which AWS service lets you quickly find the root of potential security issues to take faster actions?

        - Detective

    5. A company would like to protect its web applications from common web exploits that may affect availability, compromise security, or consume excessive resources. Which AWS service should they use?

        - AWS Web Application Firewall (WAF)

    6. Where can you find on-demand access to AWS compliance documentation and AWS agreements?

        - Artifact

    7. You can perform any kind of penetration testing on any AWS service without prior approval.

        - False

    8. You want to record configurations and changes over time. Which service allows you to do this?

        - Config

    9. A company would like to secure network communications using SSL & TLS certificates. Which AWS service can it use?

        - Certificate Manager (ACM)

    10. According to the Shared Responsibility Model, who is responsible for Patch Management?

        - AWS and the customer

    11. You want to centrally automate security checks across several AWS accounts. Which AWS service can you use?

        - Security Hub

    12. Which of the following services is managed by AWS and is used to manage encryption keys?

        - AWS KMS

    13. A company would like to automate security on EC2 instances to assess security and vulnerabilities in these instances. Which AWS service should it use?

        - Inspector

    14. Which of the following actions does NOT require the root user?

        - Access the billing dashboard

    15. According to the Shared Responsibility Model, who is responsible for protecting hardware?

        - AWS

    16. Which AWS service's ONLY role is to safeguard running applications from DDoS attacks?

        - Shield

    17. Which service is a threat detection service that continuously monitors for malicious activity and unauthorized behavior to protect your AWS accounts and workloads?

        - Amazon GuardDuty

    18. Which of the following options is NOT a situation where you should contact the AWS Abuse team?

        - Losing your MFA device

## Machine Learning

    1. You should use Amazon Transcribe to turn text into lifelike speech using deep learning.

        - False

    2. A company would like to implement a chatbot that will convert speech-to-text and recognize the customers' intentions. What service should it use?

        - Lex

    3. Which fully managed service can deliver highly accurate forecasts?

        - Forcast

    4. You would like to find objects, people, text, or scenes in images and videos. What AWS service should you use?

        - Rekognition

    5. A start-up would like to rapidly create customized user experiences. Which AWS service can help?

        - Personalize

    6. A research team would like to group articles by topics using Natural Language Processing (NLP). Which service should they use?

        -Comprehend

    7. A company would like to convert its documents into different languages, with natural and accurate wording. What should they use?

        - Translate

    8. A developer would like to build, train, and deploy a machine learning model quickly. Which service can he use?

        - SageMaker

    9. Which AWS service makes it easy to convert speech-to-text?

        - Transcribe

    10. Which of the following services is a document search service powered by machine learning?

        - Kendra

## Account Management, Billing & Support

    1.
