
#  AWS IAM & EC2 Cloud Security Project

This project demonstrates cloud security best practices using *AWS IAM* and *Amazon EC2*. It simulates a real-world scenario where an intern at AnyCompany is granted controlled access to development resources, while being restricted from production.

##  Project Overview

- Scenario: Provision IAM access for an intern with strict limitations.
- Services Used: AWS IAM and Amazon EC2.
- Goal: Grant secure access to only the development EC2 instance, while restricting access to the production EC2 instance.

##  Key Features

- Created two EC2 instances: one for development and one for production.
- Provisioned an IAM user with:
  - Fine-grained permissions using IAM policies
  - Access to only the development instance via tags
- Applied least privilege principle to prevent unnecessary access.

##  Tools & Services

- AWS IAM – For creating secure, role-based access  
- Amazon EC2 – Hosting both production and development servers  
- IAM Policies – JSON-based access rules linked to resource tags  

##  Files Included

- [AWS-security-iam-project.pdf](./AWS-security-iam-project.pdf) –  Full project documentation

##  What I Learned

- How to enforce least privilege using IAM policies  
- How to tag AWS resources for policy-based access control  
- Real-world access control strategies for cloud environments  

---

This project is part of my [AWS Cloud Projects Portfolio](../README.md).
