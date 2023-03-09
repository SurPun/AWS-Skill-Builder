## Lesson 27 - Module 5 Introduction

## Lesson 28 - Instances stores and Amazon Elastic Block Store (EBS)

- Amazon Elastic Block Store (EBS)

Knowledge check:

    - When stopping or terminating an EC2 instance, data remains available => Amazon EBS volumes

    - Best for temporary data that is not kept long term => Instance stores

    - Best for data that requires retention => Amazon EBS volumes

    - When stopping or terminating an EC2 instance, data is deleted => Instance stores.

## Lesson 29 - Amazon Simple Storage Service (Amazon S3)

- Amazon Simple Storage Service (Amazon S3)

  - Store data as objects.
  - Store objects in buckets.
  - Upload a maximum object size of 5 TB.
  - Version objects.
  - Create multiple buckets.

- Amazon S3 Standard-infrequent Access (S3 Standard-IA)

- Amazon S3 Glacier

- Knowledge Check:

  You want to store data that is infrequently accessed but must be immediately available when needed. Which Amazon S3 storage class should you use?

  - Amazon S3 Standard-IA.

    The Amazon S3 Standard-IA storage class is ideal for data that is infrequently accessed but requires high availability when needed. Both Amazon S3 Standard and Amazon S3 Standard-IA store data in a minimum of three Availability Zones. Amazon S3 Standard-IA provides the same level of availability as Amazon S3 Standard but at a lower storage price.

    The other response options are incorrect because:

        In the Amazon S3 Intelligent-Tiering storage class, Amazon S3 monitors objects’ access patterns. If you haven’t accessed an object for 30 consecutive days, Amazon S3 automatically moves it to the infrequent access tier, Amazon S3 Standard-IA. If you access an object in the infrequent access tier, Amazon S3 automatically moves it to the frequent access tier, Amazon S3 Standard.

        Amazon S3 Glacier Flexible Retrieval and Amazon S3 Glacier Deep Archive are low-cost storage classes that are ideal for data archiving. They would not be the best choice for this scenario, which requires high availability. You can retrieve objects stored in the Amazon S3 Glacier Flexible Retrieval storage class within a few minutes to a few hours. By comparison, you can retrieve objects stored in the Amazon S3 Glacier Deep Archive storage class within 12 hours.

## Lesson 30 - Amazon Elastic File System (Amazon EFS)

- Amazon EFS

  - Multiple Instances can access the data in EFS at the same time.
  - Multiple instances reading and writing simultaneously.
  - Linux file system
  - Regional resource
  - Automatically scales

- Amazon EBS

  - Volumes attach to EC2 instances
  - Availability Zone level resource
  - Need to be in the same Availability Zone to attach EC2 instances
  - Volumes do not automatically scale

# Lesson 31 - Amazon Relational Database Service (Amazon RDS)

- AWS Supported databases:
  MySql
  PostgresSQL
  Oracle
  Microsoft SQL Server

- Amazon RDS
  Automated patching
  Backups
  Redundancy
  Filover
  Disaster recovery

- Amazon Aurora
  MySQL
  PostgresSQL
  1/10th the cost of commercial databases
  Data replication
  Up to 15 read replicas
  Continuous backup to Amazon S3
  Point-in-time recovery

# Lesson 32 - Amazon DynamoDB

- Amazon DynamoDB:
  A non-relational database
  Purpose built
  Millisecond response time
  Fully managed
  Highly scalable

- Knowledge check

  What are the scenarios in which you should use Amazon Relational Database Service (Amazon RDS)? (Select TWO.)

        Using SQL to organize data

        Storing data in an Amazon Aurora database

  The other three response options are scenarios in which you should use Amazon DynamoDB.

# Lesson 33 - Amazon Redshift

- Data Warehouse

Amazon Redshift is a data warehousing service that you can use for big data analytics. It offers the ability to collect data from many sources and helps you to understand relationships and trends across your data.

# Lesson 34 - AWS Database Migration Service
