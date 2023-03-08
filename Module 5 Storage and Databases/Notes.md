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
