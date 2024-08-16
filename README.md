# VPC-Project
✨VPC with servers in private subnets and NAT✨

📝Description:
The VPC has public subnets and private subnets in two Availability Zones. Each public subnet contains a NAT gateway and a load balancer node. The servers run in the private subnets, are launched and terminated by using an Auto Scaling group, and receive traffic from the load balancer. The servers can connect to the internet by using the NAT gateway.

✨VPC Architecture

![VPC with servers in private subnets and NAT](https://github.com/user-attachments/assets/34157dc0-8e5d-4e43-a45f-bf3cf9c26173)

✔Key steps included:
Step 1: Designing a redundant VPC infrastructure with public and private subnets in multiple Availability Zones.
Step 2: Implementing Auto Scaling groups to automatically adjust server capacity based on demand.
Step 3: Configuring load balancers to distribute traffic evenly across instances.
Step 4: Setting up NAT gateways to enable private instances to access the internet.
Step 5: Optimizing security groups and network ACLs to protect the environment.

✔Below attached images of resources and a simple webpage, I create:
![Screenshot (99)](https://github.com/user-attachments/assets/9d640e4b-61bc-40fb-8a21-10865b0bcd91)
![Screenshot (101)](https://github.com/user-attachments/assets/6f1590ac-c755-4251-ac3f-a6f0dbd9ba4a)



