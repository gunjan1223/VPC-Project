# VPC-Project
✨VPC with servers in private subnets and NAT✨

The VPC has public subnets and private subnets in two Availability Zones. Each public subnet contains a NAT gateway and a load balancer node. The servers run in the private subnets, are launched and terminated by using an Auto Scaling group, and receive traffic from the load balancer. The servers can connect to the internet by using the NAT gateway


![VPC with servers in private subnets and NAT](https://github.com/user-attachments/assets/34157dc0-8e5d-4e43-a45f-bf3cf9c26173)
