Terraform AWS VPC with Public Subnet, EC2 and Nginx Web Server :

1) Project Overview :

This project demonstrates how to provision AWS cloud infrastructure using Terraform. The infrastructure includes a custom VPC, public subnet, internet gateway, route table, security group, EC2 Ubuntu instance, and Nginx web server. I also deployed and hosted a basic website on the EC2 instance using Nginx. The goal of this project is to understand Infrastructure as Code (IaC), AWS networking, and automated cloud infrastructure deployment using Terraform. |

The infrastructure includes:

- Custom VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Group
- EC2 Ubuntu Server
- Nginx Web Server

The goal of this project is to understand Infrastructure as Code (IaC) concepts and automate AWS resource creation using Terraform.

2) Technologies Used :

- Terraform          =     Infrastructure as Code
- AWS                =     Cloud Platform
- VPC                =     Network Isolation
- EC2                =     Virtual Server
- Security Groups    =     Firewall Rules
- VS Code            =     Code Editor
- AWS CLI            =     AWS Authentication
- Nginx              =     Web Server


3) AWS Resources Created :

This Terraform configuration creates the following AWS resources:

- 1 Custom VPC
- 1 Public Subnet
- 1 Internet Gateway
- 1 Route Table
- 1 Route Table Association
- 1 Security Group
- 1 EC2 Ubuntu Instance


4) Terraform Workflow :

     a) Initialize Terraform  = terraform init
     b) Review Execution Plan = terraform plan
     c) Apply Infrastructure  = terraform apply


5) Security Group Configuration :

  - SSH Access    :  Port 22 (TCP)

  - HTTP Access   :  Port 80 (TCP)


6) Challenges Faced :

- EC2 instance type compatibility issues.
- Availability Zone mismatch errors.
- Understanding Terraform resource dependencies.
