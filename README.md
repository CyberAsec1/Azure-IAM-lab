# Azure-IAM-lab
TechCorp IAM implementation - Azure Entra Id demonstrating RBAC, Security groups, user provisioning and least privilege access control 
# Azure Entra ID IAM Lab — TechCorp Implementation

## Project Overview
This lab demonstrates hands on implementation of Identity and Access Management (IAM) using Microsoft Azure Entra ID. The project simulates a fictional organization called **TechCorp** with three departments, implementing security group structure and user provisioning aligned with least-privilege access principles.

## What Was Completed

### 1. Security Groups Created
- **Engineering-Department** — Users in engineering with access to development systems
- **Finance-Department** — Users in finance with access to financial systems and budgets
- **HR-Department** — Users in HR with access to employee records and payroll systems

### 2. User Provisioning & Group Assignment
Created three users and assigned them to their respective departments:
- **Alice Chen** (alice.engineering@domain.onmicrosoft.com) → Engineering-Department
- **James Park** (finance.user@domain.onmicrosoft.com) → Finance-Department
- **Sarah Johnson** (hr.user@domain.onmicrosoft.com) → HR-Department

See: [screenshot-1-groups.png](screenshot-1-groups.png), [screenshot-2-engineering-members.png](screenshot-2-engineering-members.png), [screenshot-3-finance-members.png](screenshot-3-finance-members.png), [screenshot-4-hr-members.png](screenshot-4-hr-members.png), [screenshot-5-users-list.png](screenshot-5-users-list.png)

## Key IAM Concepts Demonstrated
- **Least Privilege Access:** Users assigned only to their department group, limiting cross-department access
- **User Provisioning:** Creating accounts and assigning them to security groups for streamlined access management
- **Security Groups:** Centralized way to manage permissions across multiple users

## Next Steps (Future Implementation)
To complete the full IAM governance framework, the following would be implemented:

### RBAC (Role-Based Access Control)
- Assign specific roles to each department group (Global Reader for read-only access, Security Reader for security monitoring, etc.)
- Implement custom roles for department-specific requirements

### Conditional Access Policies
- Enforce Multi-Factor Authentication (MFA) for all admin accounts
- Block legacy authentication protocols
- Implement device compliance requirements
- Restrict access based on location or sign-in risk

### Privileged Identity Management (PIM)
- Set up just-in-time (JIT) admin access
- Require approval workflows for elevated permissions
- Implement time-bound access to reduce standing privileges

## Skills Demonstrated
- Azure Entra ID administration and user management
- Security group design and implementation
- Understanding of least-privilege access principles
- IAM governance fundamentals
- Documentation and project organization

## Tools Used
- Microsoft Azure Entra ID
- GitHub for documentation and version control
