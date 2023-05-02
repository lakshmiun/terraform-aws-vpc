# terraform-aws-vpc
## Terraform module which creates VPC resources on AWS 

A VPC is an isolated network you create in the AWS cloud, similar to a traditional network in a data center. When you create a VPC, you need to choose three main things. 

*There are some minimum requirements you need to fulfill to create a VPC, which include:

### unique CIDR block: Y
Have to choose a unique IPv4 CIDR block for your VPC. The CIDR block must not overlap with any existing networks that are already in use in your on-premises environment

### Subnets
A subnet is a range of IP addresses in your VPC. A subnet must reside in a single Availability Zone. After you add subnets, you can deploy AWS resources in your VPC

### Routing
Use route tables to determine where network traffic from your subnet or gateway is directed.Have to configure at least one route table for your VPC to manage the traffic flow between your VPC and other networks

### Internet Gateway
If you want to connect your VPC to the internet, you will need to create and attach an Internet Gateway to your VPC.

### Security Groups
Create and configure one or more security groups to control inbound and outbound traffic to your resources within the VPC.

### Network ACLs
You may optionally configure network ACLs to provide an additional layer of security to your VPC.