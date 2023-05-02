# terraform-aws-vpc
###### Terraform module which creates VPC resources on AWS 

A VPC is an isolated network you create in the AWS cloud, similar to a traditional network in a data center. When you create a VPC, you need to choose three main things. 

* The name of your VPC.

* A Region for your VPC to live in. Each VPC spans multiple Availability Zones within the Region you choose.

* A CIDR range for your VPC. This determines the size of your network. Each VPC can have up to four /16 CIDR ranges.
