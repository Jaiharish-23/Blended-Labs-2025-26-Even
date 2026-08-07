# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## NAME : JAI HARISH R
## REG : 212224040124


## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  
(Add screenshot here)

<img width="1917" height="948" alt="image" src="https://github.com/user-attachments/assets/b60cc0a4-3aed-472b-a6e9-e529dc3c206e" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
(Add screenshot here)

<img width="1916" height="995" alt="image" src="https://github.com/user-attachments/assets/aabe754f-e2ef-45fd-94f8-2d6a11249351" />

<img width="1917" height="1005" alt="image" src="https://github.com/user-attachments/assets/6dc30824-8679-47a1-bd43-3a30e442f098" />

<img width="1917" height="991" alt="image" src="https://github.com/user-attachments/assets/649ae5c4-4211-4868-bc71-e8ed5c9fbbd7" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
(Add screenshot here)

<img width="1910" height="1057" alt="image" src="https://github.com/user-attachments/assets/cef8322d-24bc-4c7e-b318-95d7f6884008" />


<img width="1916" height="1042" alt="image" src="https://github.com/user-attachments/assets/d640230a-1ebe-47f8-b402-b51475f63c41" />

<img width="1892" height="1036" alt="image" src="https://github.com/user-attachments/assets/4c1018e2-83eb-4485-b8b0-732da58e88ab" />


## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** Your Name and (Reg No)
**Course:** Introduction to Cloud Computing  

