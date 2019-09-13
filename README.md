This is a CloudFormation Template that deploys a three-tier architecture. In this template, there is the networking component which has one VPC, six subnets (two public subnets and four private subnets) spread across two availability zones, an internet gateway, two NAT Gateways in each AZ, and the route association for the subnets. The infrastructure component which has Elastic Load Balancer, Launch configuration, and an auto scaling group. The third tier deploys a MySQL RDS with its subnet group and configuration. 

