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
<img width="1117" height="492" alt="image" src="https://github.com/user-attachments/assets/8837307c-dd6d-4561-992d-030ede4864a5" />

### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
  <img width="1103" height="505" alt="image" src="https://github.com/user-attachments/assets/e8718d51-fbd0-4807-adbe-c5732862441e" />
<img width="1132" height="508" alt="image" src="https://github.com/user-attachments/assets/0567f4d6-c7e8-423d-a8f1-13372fc1e054" />
<img width="1112" height="513" alt="image" src="https://github.com/user-attachments/assets/757a0537-2544-4a1e-b78a-50488bc4de68" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="1120" height="563" alt="image" src="https://github.com/user-attachments/assets/515dd58c-7e00-41e1-acf7-a620a4136e38" />
<img width="1133" height="583" alt="image" src="https://github.com/user-attachments/assets/2773b6ce-6ee8-4dcf-af85-44863ebdfe63" />
<img width="1110" height="548" alt="image" src="https://github.com/user-attachments/assets/47ddc5a4-eb23-4255-8d83-cee006ee7fa7" />


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
**Name:** Sarankumar.V 212224220089

**Course:** Introduction to Cloud Computing  

