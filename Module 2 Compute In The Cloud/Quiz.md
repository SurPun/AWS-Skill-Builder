# Module 2 Quiz

1.  You want to use an Amazon EC2 instance for a batch processing workload. What would be the best Amazon EC2 instance type to use?

    Compute optimized.

    The other response options are incorrect because:

        - General purpose instances provide a balance of compute, memory, and networking resources. This instance family would not be the best choice for the application in this scenario. Compute optimized instances are more well suited for batch processing workloads than general purpose instances.

        - Memory optimized instances are more ideal for workloads that process large datasets in memory, such as high-performance databases.

        - Storage optimized instances are designed for workloads that require high, sequential read and write access to large datasets on local storage. The question does not specify the size of data that will be processed. Batch processing involves processing data in groups. A compute optimized instance is ideal for this type of workload, which would benefit from a high-performance processor.

2.  What are the contract length options for Amazon EC2 Reserved Instances? (Select TWO.)

    1 year
    3 years

    Reserved Instances require a commitment of either 1 year or 3 years. The 3-year option offers a larger discount.

3.  You have a workload that will run for a total of 6 months and can withstand interruptions. What would be the most cost-efficient Amazon EC2 purchasing option?

    Spot Instance.

    The other response options are incorrect because:

        - Reserved Instances require a contract length of either 1 year or 3 years. The workload in this scenario will only be running for 6 months.

        - Dedicated Instances run in a virtual private cloud (VPC) on hardware that is dedicated to a single customer. They have a higher cost than the other response options, which run on shared hardware.

        - On-Demand Instances fulfill the requirements of running for only 6 months and withstanding interruptions. However, a Spot Instance would be the best choice because it does not require a minimum contract length, is able to withstand interruptions, and costs less than an On-Demand Instance.

4.  Which process is an example of Elastic Load Balancing?

    Ensuring that no single Amazon EC2 instance has to carry the full workload on its own.

    Elastic Load Balancing is the AWS service that automatically distributes incoming application traffic across multiple resources, such as Amazon EC2 instances. This helps to ensure that no single resource becomes overutilized.

    The other response options are all examples of Auto Scaling.

5.  You want to deploy and manage containerized applications. Which service should you use?

    Amazon Elastic Kubernetes Service (Amazon EKS).

    Amazon EKS is a fully managed Kubernetes service. Kubernetes is open-source software that enables you to deploy and manage containerized applications at scale.

    The other response options are incorrect because:

        - AWS Lambda is a service that lets you run code without provisioning or managing servers.

        - Amazon Simple Queue Service (Amazon SQS) is a service that enables you to send, store, and receive messages between software components through a queue.

        - Amazon Simple Notification Service (Amazon SNS) is a publish/subscribe service. Using Amazon SNS topics, a publisher publishes messages to subscribers.
