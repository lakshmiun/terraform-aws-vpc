# terraform-aws-vpc
## Terraform module which creates VPC resources on AWS 

A VPC is an isolated network you create in the AWS cloud, similar to a traditional network in a data center. When you create a VPC, you need to choose three main things. 

* The name of your VPC.

* A Region for your VPC to live in. Each VPC spans multiple Availability Zones within the Region you choose.

* A CIDR range for your VPC. This determines the size of your network. Each VPC can have up to four /16 CIDR ranges.

The VPC has one subnet in each of the Availability Zones in the Region, EC2 instances in each subnet, 
and an internet gateway to allow communication between the resources in your VPC and the internet.

### Subnets
A subnet is a range of IP addresses in your VPC. A subnet must reside in a single Availability Zone. After you add subnets, you can deploy AWS resources in your VPC

### Routing
Use route tables to determine where network traffic from your subnet or gateway is directed.