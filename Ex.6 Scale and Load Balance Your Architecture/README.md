# Lab 6 – Scale and Load Balance Your Architecture

## Title

# Scale and Load Balance Your Architecture
## Author : JAI HARISH R
## Reg no : 212224040124 Date : 03/09/26

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

Task 1: Review Existing Architecture
Students review the existing EC2-based application architecture created in previous experiments.

Task 2: Create a Launch Template
Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

Task 3: Create an Auto Scaling Group
Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

Task 4: Configure an Application Load Balancer
Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

Task 5: Register Auto Scaling Group with Load Balancer
Students attach the Auto Scaling Group to the target group of the load balancer.

Task 6: Configure Scaling Policies
Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

Task 7: Test Load Balancing and Scaling
Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Output Screenshots 

<img width="1600" height="866" alt="image" src="https://github.com/user-attachments/assets/0402b5d5-46b3-420d-9589-e1af439674a2" />

<img width="1600" height="878" alt="image" src="https://github.com/user-attachments/assets/660c6673-d032-4471-9dfe-b4bb5f403d41" />

<img width="1600" height="877" alt="image" src="https://github.com/user-attachments/assets/1a74178e-bea2-49cc-a1df-8ce0eded14b4" />

<img width="1600" height="872" alt="image" src="https://github.com/user-attachments/assets/42c52c2f-13af-4aae-a306-3160f42a5e79" />

<img width="1600" height="910" alt="image" src="https://github.com/user-attachments/assets/83a2bbcc-65ac-481b-975e-bef4457bbcc7" />

<img width="1600" height="866" alt="image" src="https://github.com/user-attachments/assets/61af30b5-66e9-4c38-99d4-e7a8c4ed6b87" />


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
