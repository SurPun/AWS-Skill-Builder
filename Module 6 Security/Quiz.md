# Module 6 quiz

1.  Which statement best describes an IAM policy?

    - A document that grants or denies permissions to AWS services and resources.

    IAM policies provide you with the flexibility to customize users’ levels of access to resources. For instance, you can allow users to access all the Amazon S3 buckets in your AWS account or only a specific bucket.

    The other response options are incorrect because:

         Multi-factor authentication (MFA) is an authentication process that provides an extra layer of protection for your AWS account.

         An IAM role is an identity that you can assume to gain temporary access to permissions.

         The root user identity is the identity that is established when you first create an AWS account.

2.  An employee requires temporary access to create several Amazon S3 buckets. Which option would be the best choice for this task?

    - An IAM role is an identity that you can assume to gain temporary access to permissions. When someone assumes an IAM role, they abandon all permissions that they had under a previous role and assume the permissions of the new role. IAM roles are ideal for situations in which access to services or resources needs to be granted temporarily instead of long-term.

    The other response options are incorrect because:

        The AWS account root user is established when you first create an AWS account. As a best practice, do not use the root user for everyday tasks.

        Although you can attach IAM policies to an IAM group, this would not be the best choice for this scenario because the employee only needs to be granted temporary permissions.

        Service control policies (SCPs) enable you to centrally control permissions for the accounts in your organization. An SCP is not the best choice for granting temporary permissions to an individual employee.

3.  Which statement best describes the principle of least privilege?

    - Granting only the permissions that are needed to perform specific job tasks.

    When you grant permissions by following the principle of least privilege, you prevent users or roles from having more permissions than needed to perform specific job tasks. For example, cashiers in the coffee shop should be given access to the cash register system. As a best practice, grant IAM users and roles a minimum set of permissions and then grant additional permissions as needed.

4.  Which service helps protect your applications against distributed denial-of-service (DDoS) attacks?

    - AWS Shield.

    As network traffic comes into your applications, AWS Shield uses a variety of analysis techniques to detect potential DDoS attacks in real time and automatically mitigates them.

    The other response options are incorrect because:

        Amazon GuardDuty is a service that provides intelligent threat detection for your AWS infrastructure and resources. It identifies threats by continuously monitoring the network activity and account behavior within your AWS environment.

        Amazon Inspector checks applications for security vulnerabilities and deviations from security best practices, such as open access to Amazon EC2 instances and installations of vulnerable software versions.

        AWS Artifact is a service that provides on-demand access to AWS security and compliance reports and select online agreements.

5.  Which task can AWS Key Management Service (AWS KMS) perform?

    - Create cryptographic keys.

    AWS Key Management Service (AWS KMS) enables you to perform encryption operations through the use of cryptographic keys. A cryptographic key is a random string of digits used for locking (encrypting) and unlocking (decrypting) data. You can use AWS KMS to create, manage, and use cryptographic keys. You can also control the use of keys across a wide range of services and in your applications.

    The other response options are incorrect because:

        You can configure multi-factor authentication (MFA) in AWS Identity and Access Management (IAM).

        You can update the AWS account root user password in the AWS Management Console.

        You can assign permissions to users and groups in AWS Identity and Access Management (IAM).
