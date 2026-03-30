🚀 Terraform Project: EC2 Instances Setup with Shared RDS Database

Designed and deployed a practical AWS architecture using Terraform where two EC2 instances connect to a single RDS database. This mirrors a common production setup where multiple application servers rely on a centralized database for consistency and scalability.

🔹 Architecture Overview

* Two EC2 instances deployed in separate Availability Zones
* Both instances connected to a single RDS database
* Custom VPC with public subnets and internet access
* Controlled access using a security group
This setup ensures better availability, simplified data management, and horizontal scalability.

🔹 Resources Purpose (Quick Overview)

1. VPC: Provides an isolated network environment for all resources
2. Subnets: Distribute resources across Availability Zones for resilience
3. Network Interfaces: Enable explicit network attachment and control for EC2
4. Security Group: Manages access (SSH, HTTP, HTTPS, MySQL)
5. Internet Gateway: Allows communication between VPC and the internet
6. Route Table: Defines how traffic flows within the network
7. Route Associations: Connect subnets to the route table
8. Elastic IPs: Provide fixed public IP addresses for EC2 instances
9. EC2 Instances: Act as application servers
10. DB Subnet Group: Specifies subnets for RDS deployment
11. RDS Instance: Central database shared by both EC2 servers

🔹 Key Takeaways
✔ Built a multi-AZ architecture using Terraform
✔ Enabled multiple servers to share a single database
✔ Gained hands-on experience with AWS components
✔ Good understanding of Infrastructure as Code (IaC)

hashtag#Terraform hashtag#AWS hashtag#DevOps hashtag#Cloud hashtag#InfrastructureAsCode hashtag#EC2 hashtag#RDS
