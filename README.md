## Ex.4 Deployment and configuration of a Private Cloud in AWS
```
Name: Alan Samuel Vedanayagam
Reg. No: 212223040012
```

## Aim:
To set up of a Private Cloud in AWS.
## Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),involves creating a logically isolated virtual network that you can use to launch AWS resources. This provides you with full control over your virtual networking environment,including resource placement, connectivity, and security.Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console. Next, add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.

## Procedure:

1. Plan Your VPC:
● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.
2. Create Your VPC:
• Sign in to AWS Management Console: Access the VPC console and navigate to
the VPC dashboard.
• Choose "Create VPC": Initiate the VPC creation process.
• Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
• other necessary settings.
• Create subnets: Define subnets within your VPC to isolate different parts of your
• network.
• Create route tables: Specify how traffic is routed within and outside the VPC.
• Create security groups: Define access control rules for your resources.
3. Deploying Resources:
• Launch EC2 instances: Create and launch virtual machines within your VPC.
• Set up RDS instances: Deploy databases for your applications.
• Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.
• Deploy other AWS services: Integrate other services like S3 for storage and
Lambda for serverless computing.
4.Managing and Monitoring:
• Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.
• Configure logging and auditing: Track access and activity within your VPC for
security and compliance.
• Implement security best practices: Regularly review and update your security
configuration.
• Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

## Snap Shot:
![image](https://github.com/user-attachments/assets/14113b49-6207-42a2-953f-b22fb6882753)

Snapshot 1: Create VPC

![image](https://github.com/user-attachments/assets/de3fe3c0-1843-48aa-9de8-cf716f7e32be)

Snapshot 2: Configuring Subnets

![image](https://github.com/user-attachments/assets/ce4b82b5-0a7f-4bef-afc3-579b83152fdf)

Snapshot 3: Configure Subnets

![image](https://github.com/user-attachments/assets/1bd2178e-67ed-49fe-95b6-d91463aa8287)

Snapshot 4: Setting Internet gateway

![image](https://github.com/user-attachments/assets/91528f4f-4867-495b-bb2d-abb20e2c9289)

Snapshot 5: Setting Internet gateway

![image](https://github.com/user-attachments/assets/dd627b48-a160-48b1-a34f-181bda58d661)

Snapshot 6: Setting Internet gateway

![image](https://github.com/user-attachments/assets/2603c4ec-1e5d-4540-abee-2bb3de37b95c)

Snapshot 7: Creating route table

![image](https://github.com/user-attachments/assets/6bd3cece-23d9-4c51-82a9-99569ea0482c)

Snapshot 8: Configuring route table

![image](https://github.com/user-attachments/assets/3d28f7f6-dea2-495c-8164-fbe9f4f0cfcc)

Snapshot 9: Editing routes

![image](https://github.com/user-attachments/assets/efac5508-e527-4348-9466-31c7830241ac)

Snapshot 10: Creating route table

## Result:
Thus, a private cloud on AWS involves using VPCs has been created for a dedicated, isolated network where we can manage our resources and control access according to our requirements.
