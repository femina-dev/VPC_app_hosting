# VPC_app_hosting
Deploying Application in VPC - Private subnet and NAT

Implementation of #VPC with servers in private subnets and NAT replicating a Production environment.

Implementation:

Create a VPC with a public subnet and a private subnet in two Availability Zones, and a NAT gateway in each Availability Zone.
To improve resiliency, deployed the servers in two Availability Zones, by using an Auto Scaling group and an Application Load Balancer with targets.
For additional security, deployed the servers in private subnets. The servers receive requests through the load balancer.
Created a bastion host to connect with instances in the Virtual subnet.
The servers can connect to the internet by using a NAT gateway. To improve resiliency, deploy the NAT gateway in both Availability Zones.
Tested application and validated the traffic flow through both availability zones. 


Please refer to the Overview and screenshots
