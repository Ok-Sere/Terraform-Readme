# Mini Project: Terraform EC2 Instance and AMI Creation

## Project Purpose

In this mini project, Terraform is used to automate the creation of an EC2 instance on AWS and then create an Amazon Machine Image (AMI) from that instance.

---

## Objectives

1. **Terraform Configuration:**  
   - Learn how to write basic Terraform configuration files.

2. **EC2 Instance Creation:**  
   - Use Terraform to create an EC2 instance on AWS.

3. **AMI Creation:**  
   - Automate the creation of an AMI from the created EC2 instance.

---

## Project Tasks

### Task 1: Terraform Configuration for EC2 Instance

- Create a new directory for your Terraform project.
- Write Terraform code to create an EC2 instance (specify instance type, key pair, security group, etc.).
- Initialize the Terraform project using `terraform init`.
- Apply the Terraform configuration using `terraform apply`.

### Task 2: AMI Creation

- Extend your Terraform configuration to include the creation of an AMI.
- Use provisioners in Terraform to execute commands on the EC2 instance after it’s created (optional).
- Configure Terraform to create an AMI from the provisioned EC2 instance.
- Apply the updated Terraform configuration to create the AMI using `terraform apply`.

---

## Screenshots & Explanations

### 1. AWS CLI and Terraform Installation
![1](./img/1.%20cli%20and%20terraform.jpg)
*Shows the successful installation of AWS CLI and Terraform.*

### 2. Selecting an AMI
![2](./img/1a.%20ami.jpg)
*Shows how to select a suitable AMI from the AWS Console for use in your Terraform script.*

### 3. Key Pair Creation
![1](./img/1b.%20keypair.jpg)
*Shows the creation or selection of an AWS key pair for SSH access to the EC2 instance.*

### 4. Writing the Terraform Script
![1](./img/2b.%20correct%20script.jpg)
![1](./img/2c.%20correct%20script%202.jpg)
*Shows the correct Terraform configuration for creating a VPC, subnet, security group, EC2 instance, and AMI.*

### 5. Initializing Terraform
![1](./img/3.%20Terraform%20init.jpg)
*Shows the output of running `terraform init` to initialize the project.*

### 6. Applying Terraform Configuration
![1](./img/4.%20apply%201.jpg)
![1](./img/5.%20apply%202.jpg)
*Shows the process of running `terraform apply` and confirming resource creation.*

### 7. AWS Console Verification
![1](./img/6.%20aws.jpg)
![1](./img/7.%20vpc.jpg)
*Shows verification of resources (EC2, VPC, etc.) in the AWS Console.*

### 8. AMI Creation and Results
![1](./img/8.%20ami.jpg)
![1](./img/9.%20ami%20terminal.jpg)
![1](./img/10.%20ami%20result.jpg)
*Shows the creation of the AMI and the results in the AWS Console and terminal.*

---

## Summary

This project demonstrates how to use Terraform to automate the provisioning of AWS infrastructure, specifically the creation of an EC2 instance and an Amazon Machine Image (AMI) from that instance. By following the documented steps and screenshots, you will learn how to:

- Set up your environment with AWS CLI and Terraform.
- Write and apply Terraform configuration files to create a VPC, subnet, security group, and EC2 instance.
- Select and use a suitable AMI and key pair for your deployment.
- Extend your configuration to create an AMI from your running EC2 instance.
- Verify your resources in the AWS Console and clean up when finished.

The included screenshots provide a visual guide for each stage, making it easier to follow along and understand the process. This hands-on mini project is ideal for beginners looking to gain practical experience with Infrastructure as Code (IaC) using Terraform and AWS.



