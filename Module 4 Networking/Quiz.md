# Module 4 Quiz

1.  Your company has an application that uses Amazon EC2 instances to run the customer-facing website and Amazon RDS database instances to store customers’ personal information. How should the developer configure the VPC according to best practices?

    - Place the Amazon EC2 instances in a public subnet and the Amazon RDS databases instances in a private subnet.

    A subnet is a section of a VPC in which you can group resources based on security or operational needs. Subnets can be public or private.

    Public subnets contain resources that need to be accessible by the public, such as an online store’s website.

    Private subnets contain resources that should be accessible only through your private network, such as a database that contains customers’ personal information and order histories.

2.  Which component can be used to establish a private dedicated connection between your company’s data center and AWS?

    - AWS Direct Connect.

    The other response options are incorrect because:

    A private subnet is a section of a VPC in which you can group resources that should be accessed only through your private network. Although it is private, it is not used for establishing a connection between a data center and AWS.
    DNS stands for Domain Name System, which is a directory used for matching domain names to IP addresses.

    A virtual private gateway enables you to create a VPN connection between your VPC and a private network, such as your company’s data center. Although this connection is private and encrypted, it travels through the public internet, not through a dedicated connection.

3.  Which statement best describes security groups?

    - Security groups are stateful and deny all inbound traffic by default.

    Security groups are stateful. This means that they use previous traffic patterns and flows when evaluating new requests for an instance.

    By default, security groups deny all inbound traffic, but you can add custom rules to fit your operational and security needs.

4.  Which component is used to connect a VPC to the internet?

    - Internet gateway.

    The other response options are incorrect because:

         A public subnet is a section of a VPC that contains public-facing resources.

         An edge location is a site that Amazon CloudFront uses to store cached copies of your content for faster delivery to customers.

         A security group is a virtual firewall that controls inbound and outbound traffic for an Amazon EC2 instance.

5.  Which service is used to manage the DNS records for domain names?

    - Amazon Route 53.

    Amazon Route 53 is a DNS web service. It gives developers and businesses a reliable way to route end users to internet applications that host in AWS.

    Another feature of Route 53 is the ability to manage the DNS records for domain names. You can transfer DNS records for existing domain names managed by other domain registrars. You can also register new domain names directly in Route 53.

    The other response options are incorrect because:

        Amazon Virtual Private Cloud (Amazon VPC) is a service that enables you to provision an isolated section of the AWS Cloud. In this isolated section, you can launch resources in a virtual network that you define.

        AWS Direct Connect is a service that enables you to establish a dedicated private connection between your data center and VPC.

        Amazon CloudFront is a content delivery service. It uses a network of edge locations to cache content and deliver content to customers all over the world.
