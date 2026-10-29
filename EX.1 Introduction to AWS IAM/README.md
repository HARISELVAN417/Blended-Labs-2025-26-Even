# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

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
<img width="1907" height="979" alt="Screenshot 2026-10-14 141424" src="https://github.com/user-attachments/assets/249a94de-f368-4f4d-a527-44686a16bd92" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**
  <img width="1907" height="979" alt="Screenshot 2026-10-14 141424" src="https://github.com/user-attachments/assets/24dffa26-9f62-41c8-9e61-1d601c95f702" />

  <img width="1906" height="976" alt="Screenshot 2026-10-14 141448" src="https://github.com/user-attachments/assets/dd37b65a-4d64-462f-8833-8a3bd3fbe55b" />

  <img width="1904" height="983" alt="Screenshot 2026-10-14 141503" src="https://github.com/user-attachments/assets/2a5ff148-921b-471d-a59c-eb563b48b4ce" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="1915" height="976" alt="Screenshot 2026-10-14 141932" src="https://github.com/user-attachments/assets/86cfe56f-4fd5-4026-85aa-d23a23ee4201" />

<img width="1911" height="967" alt="Screenshot 2026-10-14 142057" src="https://github.com/user-attachments/assets/66bc2707-953c-44ac-ad58-1e48051f1bba" />

<img width="1915" height="970" alt="Screenshot 2026-10-14 142355" src="https://github.com/user-attachments/assets/e01f695f-62ac-4003-8141-dcc036aec1d2" />

<img width="1910" height="971" alt="Screenshot 2026-10-14 142640" src="https://github.com/user-attachments/assets/1758775a-c73a-4588-a322-df33d0a3f268" />

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
**Name:** **HARISELVAN(212224040103)**
**Course:** Introduction to Cloud Computing  

