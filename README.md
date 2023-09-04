# classic-3tier-app-architecture
Visual Representation of a 3-Tier Application Architecture on AWS

### Public Tier - AWS Application Load Balancer (ALB) running in a Public Subnet, can be reached from the internet

### Application Tier - EC2 instances or ASG running in a Private Subnet, but can initiate outbound connection to the internet, but not reachable from the Internet

### DataStore Tier - A PostgreSQL running in a Private Subnet, All traffic in this subnet is completely local to the VPC


![The Architecture Diagram]()
