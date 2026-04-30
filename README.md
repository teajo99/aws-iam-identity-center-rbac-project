Architecture diagram
![image alt](https://github.com/teajo99/aws-iam-identity-center-rbac-project/blob/465e53699f6637b41f72746599ba2c1bc66d28bd/IAM%20PROJECT1.png)


# 🔐 AWS IAM Identity Center – Role-Based Access Control (RBAC) Project

## 📌 Overview

This project demonstrates how organizations manage secure user access using **AWS IAM Identity Center**.

It simulates a real-world enterprise (such as a bank) where employees are grouped based on job function, and access is controlled using **permission sets and group-based policies**.

This follows the **least privilege principle**, ensuring users only access what they need.

---

## 🎯 Objective

To design and implement a cloud identity management system that:

- Controls user access using groups and permission sets  
- Prevents unauthorized access to sensitive systems  
- Demonstrates centralized identity management in AWS  
- Simulates enterprise-level access control design  

---

## 🏦 Real-World Scenario

In a banking environment:

- Traders access trading-related systems  
- Accountants access financial data  
- Risk Officers access audit and monitoring logs  

Each user is restricted to only the resources required for their job function.

---

## 🛠️ AWS Services Used

- AWS IAM Identity Center  
- User Management  
- Group Management  
- Permission Sets  
- AWS Access Portal (SSO Login)  

---

## 👥 Identity Structure

| Group Name       | Purpose / Access Level            |
|------------------|----------------------------------|
| Traders          | Access to trading systems        |
| Accountants      | Access to financial records      |
| Risk Officers    | Access to audit logs & monitoring |

---

## 📂 Project Structure


---

## 📄 JSON Configuration Files

This project includes structured JSON files representing:

- Users in the system  
- Group assignments  
- Permission sets mapped to access levels  

These files simulate how identity structures are designed in real cloud environments.

---

## 📸 Demo Highlights

- AWS IAM Identity Center configured successfully  
- Users and groups created  
- Permission sets assigned to groups  
- Access tested using Risk Officer login  
- Verified restricted access behavior  

---

## 🔐 Key Concepts Demonstrated

- Identity and Access Management (IAM)  
- Role-Based Access Control (RBAC) using groups  
- Permission-based access design  
- Least privilege security model  
- Centralized identity management  

--
---

## 💡 Key Learning Outcome

This project demonstrates how cloud architects design secure access systems where:

- Users are grouped by function  
- Permissions are centrally managed  
- Access is restricted based on need  
- Security and compliance are enforced  

---

## 🚀 Future Improvements

- Add Multi-Factor Authentication (MFA)  
- Integrate AWS Organizations (multi-account setup)  
- Automate user provisioning  
- Add CloudTrail logging for audit tracking  

---

## 👨‍💻 Author

Aspiring Cloud Architect focused on AWS Cloud Security, Identity Management, and Scalable Cloud Architecture.

---

## 📌 Note

This project is part of a hands-on cloud learning journey focused on building real-world AWS architecture skills.
