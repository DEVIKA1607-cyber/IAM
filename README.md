IAM
EX - 6 Implementation Of Identity Management (Amazon Iam) For Your Team.
NAME: D DEVIKA
REG NO: 212224100010
Aim
To implement Identity and Access Management (IAM) in AWS to securely control access to resources by creating and managing IAM users, groups, roles, and policies for team collaboration.

Algorithm
Sign in to the AWS Management Console.
Navigate to the IAM service.
Create IAM groups with defined policies (e.g., Admin, Developer).
Create IAM users and assign them to appropriate groups.
Create IAM roles if cross-account or service-based access is needed.
Attach permissions using managed or custom policies.
Enable MFA (Multi-Factor Authentication) for users.
Monitor access using IAM Access Analyzer and CloudTrail.
Procedure
1. Access IAM
Go to AWS Console → Services → IAM
2. Create IAM Groups
Click Groups → Create New Group
Name the group (e.g., Admins, Developers)
Attach predefined or custom policies (e.g., AmazonEC2FullAccess, ReadOnlyAccess)
3. Create IAM Users
Click Users → Add Users
Provide usernames
Choose access type:
Programmatic access
AWS Management Console access
Assign users to the appropriate IAM group
4. Create IAM Roles (Optional)
Go to Roles → Create Role
Select a use case:
AWS service
Another AWS account
Attach policies as required
5. Apply Policies
Use AWS Managed Policies or create custom policies using JSON
Attach them to:
Users
Groups
Roles
6. Enable Multi-Factor Authentication (MFA)
Go to the IAM user → Security credentials
Click Manage MFA
Choose Virtual MFA device (e.g., Google Authenticator)
7. Monitor IAM Usage
Use IAM Access Analyzer to review access
Use AWS CloudTrail to audit actions and access logs
Scenario
Screenshot 2025-11-15 at 11 03 27 AM
Output
Screenshot 2025-11-15 at 11 07 54 AM Screenshot 2025-11-15 at 11 07 50 AM
Result
Successfully implemented identity and access management using Amazon IAM, enabling secure, role-based access control and ensuring team collaboration with best security practices.
