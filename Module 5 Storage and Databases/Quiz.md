# Module 5 Quiz

1.  Which Amazon S3 storage classes are optimized for archival data? (Select TWO.)

    - Amazon S3 Glacier Flexible Retrieval

    - Amazon S3 Glacier Deep Archive

    Objects stored in the Amazon S3 Glacier Flexible Retrieval storage class can be retrieved within a few minutes to a few hours. By comparison, objects that are stored in the Amazon S3 Glacier Deep Archive storage class can be retrieved within 12 hours.

    The other response options are incorrect because:

         Amazon S3 Standard is a storage class that is ideal for frequently accessed data, not archival data.

         Amazon S3 Intelligent-Tiering monitors access patterns of objects and automatically moves them between the Amazon S3 Standard and Amazon S3 Standard-IA storage classes. It is not designed for archival data.

         Amazon S3 Standard-IA is ideal for data that is infrequently accessed but requires high availability when needed.

2.  Which statement or statements are TRUE about Amazon EBS volumes and Amazon EFS file systems?

    - EBS volumes store data within a single Availability Zone. Amazon EFS file systems store data across multiple Availability Zones.

    An EBS volume must be located in the same Availability Zone as the Amazon EC2 instance to which it is attached.

    Data in an Amazon EFS file system can be accessed concurrently from all the Availability Zones in the Region where the file system is located.

3.  You want to store data in an object storage service. Which AWS service is best for this type of storage?

    - Amazon Simple Storage Service (Amazon S3).

    The other response options are incorrect because:

        Amazon Managed Blockchain is a service that you can use to create and manage blockchain networks with open-source frameworks. Blockchain is a distributed ledger system that lets multiple parties run transactions and share data without a central authority.

        Amazon Elastic File System (Amazon EFS) is a scalable file system used with AWS Cloud services and on-premises resources. It does not store data as object storage.

        Amazon Elastic Block Store (Amazon EBS) is a service that provides block-level storage volumes that you can use with Amazon EC2 instances.

4.  Which statement best describes Amazon DynamoDB?

    - A serverless key-value database service.

    Amazon DynamoDB is a key-value database service. It is serverless, which means that you do not have to provision, patch, or manage servers.

    The other response options are incorrect because:

        A service that enables you to run relational databases in the AWS Cloud describes Amazon Relational Database Service (Amazon RDS).

        A service that you can use to migrate relational databases, nonrelational databases, and other types of data stores describes AWS Database Migration Service (AWS DMS).

        An enterprise-class relational database describes Amazon Aurora.

5.  Which service is used to query and analyze data across a data warehouse?

    - Amazon Redshift.

    Amazon Redshift is a data warehousing service that you can use for big data analytics. Use Amazon Redshift to collect data from many sources and help you understand relationships and trends across your data.

    The other response options are incorrect because:

        Amazon Neptune is a graph database service. You can use Amazon Neptune to build and run applications that work with highly connected datasets, such as recommendation engines, fraud detection, and knowledge graphs.

        Amazon DocumentDB is a document database service that supports MongoDB workloads.

        Amazon ElastiCache is a service that adds caching layers on top of your databases to help improve the read times of common requests.
