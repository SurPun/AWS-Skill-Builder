## Lesson 21 - Module 4 Introduction

- Amazon Virtual Private Cloud (VPC)

## Lesson 22 - Connectivity to AWS

- VPC
- Subnet
- Internet Gateway
- Virtual Private Gateway
- AWS Direct Connect

## Lesson 23 - Subnets and network access control lists

- Network Hardening
- Application Security
- User Identity
- Authentication and Authorization
- Distributed denial of service prevention
- Data integrity
- Encryption

- Network Access Control List (Network ACL)

- Knowledge Check:

  1. For this review exercise, imagine that your company is launching an online photo storage application. Help determine which VPC component should be used for certain aspects of the application.

  In the following, match each part of the application to the correct VPC component:

        - Isolate databases containing customers' personal information => Private subnet

        - Create a vpn connection between the VPC and the internal corporate network => Virtual private gateway

        - Support the customer-facing website => Public subnet

        - Establish a dedicated connection between the on-premises data center and the VPC => AWS Direct Connect.

  2. Which statement best describes an AWS account’s default network access control list?

  It is stateless and allows all inbound and outbound traffic.

        - Network access control lists (ACLs) perform stateless packet filtering. They remember nothing and check packets that cross the subnet border each way: inbound and outbound.

        - Each AWS account includes a default network ACL. When configuring your VPC, you can use your account’s default network ACL or create custom network ACLs.

        - By default, your account’s default network ACL allows all inbound and outbound traffic, but you can modify it by adding your own rules. For custom network ACLs, all inbound and outbound traffic is denied until you add rules to specify which traffic should be allowed. Additionally, all network ACLs have an explicit deny rule. This rule ensures that if a packet doesn’t match any of the other rules on the list, the packet is denied.

## Lesson 24 - Global Networking
