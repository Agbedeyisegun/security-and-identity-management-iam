#   Capstone Project Bash Scripting for Multiplication Table 


## Readme URL Below: 

https://github.com/Agbedeyisegun/3mtt-project/blob/main/darey.io/security-and-identity-management-iam
/README.md


## Below are the screenshots of the steps.



- Step 1 
Screenshot of aws console in iam page with created policy called "developers" in ec2 with full access for all resources for the developers Team in a fintech company named Zappy e-Bank in other to ensure policy base environment for the organisation cloud infrastucture setup. 
![developer-policy created](img/step1-developer-policy-created-successfully.jpg)


- Step 2 
Screenshot of aws console in iam page with created group called "Development Team" in the fintech company named Zappy e-Bank in other to ensure group permission base environment for the organisation cloud infrastucture setup. 
![development group created](img/step2-developer-added-to-development-team-group-successfully.jpg)





- Step 3 
Screenshot of aws console in iam page with created policy called "analyst-policy" in s3 Bucket with full access for all resources for the Analyst Team in a fintech company named Zappy e-Bank in other to ensure policy base environment for the organisation cloud infrastucture setup. 
![analyst-policy created](img/step3-analyst-policy-created-successfully.jpg)






- Step 4 
Screenshot of aws console in iam page with created group called "Analyst Team" in the fintech company named Zappy e-Bank in other to ensure group permission base environment for the organisation cloud infrastucture setup. 
![analyst group created](img/step4-analyst-added-to-analyst-team-group-successfully.jpg)




- Step 5 
Screenshot of a creation of a user called john to be added to the "Development Team" in other to ensure group permission base environment for the organisation cloud infrastucture setup. 
![user mary creation details](img/step5-developer-john-creation-auto-passwd.jpg)





- Step 6 
Screenshot of review of user called john to be added to the "Development Team" 
![user john creation review](img/step6-developer-john-creation-review.jpg)




- Step 7 
Screenshot of successful creation of the user called john to be added to the "Development Team" with auto-generation password set with  download password file creation. 
![user john ready](img/step7-developer-john-creation-review-successful-with-passwd.jpg)





- Step 8 
Screenshot of successful creation of the user called john added to the "Development Team"  and "developers" policy. 
![user john added to team with the policy](img/step8-developer-john-creation-overview.jpg)





- Step 9 
Screenshot of a creation of a user called mary to be added to the "Analyst Team" in other to ensure group permission base environment for the organisation cloud infrastucture setup. 
![user mary creation details](img/step9-analyst-mary-creation-auto-passwd.jpg)





- Step 10 
Screenshot of review of user called mary to be added to the "Analyst Team" 
![user mary creation review](img/step10-analyst-mary-creation-review.jpg)





- Step 11 
Screenshot of successful creation of the user called mary to be added to the "Analyst Team" with auto-generation password set with  download password file creation. 
![user mary ready](img/step11-analyst-mary-creation-review-successful-with-passwd.jpg)





- Step 12 
Screenshot of successful creation of the user called mary added to the "Analyst Team"  and "Analyst-policy" policy. 
![user mary added to team with the policy](img/step12-analyst-mary-creation-overview.jpg)




- Step 13 
Screenshot of aws with user john trying to login with his auto-generated password as one of the developers employed to with the "Development Team" that have "developers" policy attached to his role in Zappy e-Bank. 
![user john first time login](img/step13-developer-john-login-with-auto-passwd-changed.jpg)






- Step 14 
Screenshot of aws with user john with force password changed for the first time of login to the platform as developer.
![user john force password change](img/step14-developer-john-login-with-auto-passwd-changed.jpg)




- Step 15 
Screenshot of aws with user john with force password changed successfully.
![user john password change successfully](img/step15-developer-john-login-with-auto-passwd-changed-successfully.jpg)


 


- Step 16

Screenshot of aws with user john logged in to the console successfully after chnaging the password.
![user john logged in to the console](img/step16-developer-john-login-page-before-mfa.jpg)



- Step 17

Screenshot of aws with main user activate mfa to increase the security of the user called john in other to reduce access to fictious access to the system.
![user john mfa activation](img/step17-developer-john-mfa-creation.jpg)





- Step 18

Screenshot of aws with main user using google aunthenticator already installed on the user john
's phone for authenticating his access to the company
's plaform on aws.
![user john mfa google auth](img/step18-developer-john-mfa-creation-google-auth.jpg)




- Step 19

Screenshot of aws with main user added google aunthenticator successfully for user john.
![user john mfa google auth added](img/step19-developer-john-mfa-google-auth-added.jpg)



- Step 20

Screenshot of aws with main user activate mfa to increase the security of the user called mary in other to reduce access to fictious access to the system.
![user mary mfa activation](img/step20-analyst-mary-mfa-creation.jpg)




- Step 21

Screenshot of aws with main user using google aunthenticator already installed on the user mary
's phone for authenticating his access to the company
's plaform on aws.
![user mary mfa google auth](img/step21-analyst-mary-mfa-creation-google-auth.jpg)



- Step 22

Screenshot of aws with main user added google aunthenticator successfully for user mary.
![user mary mfa google auth added](img/step22-analyst-mary-mfa-google-auth-added.jpg)





- Step 23

Screenshot of aws user john login page trying to test his access to ec2 instance that was given access to on the company's platform to be able to create an application to float the company's website and edit it. He created an instance called "production-app" and it is running successfully as expected.
![user john access granted tested](img/step23-developer-john-ec2-creation-access.jpg)




- Step 24

Screenshot of aws user john login page trying to test his access if it will work on resources that he did not have access to  which is s3 storage bucket as it is out of his job purview and he got access denied, when trying to create a storage bucket as expected.
![user john access denied tested](img/step24-developer-john-s3-creation-access-denied.jpg)





- Step 25

Screenshot of aws with user called mary showing the mfa activated for her during login in other to reduce fictious access to the system.
![user mary mfa activation tested](img/step25-analyst-mary-mfa-creation-tested.jpg)




- Step 26 
Screenshot of aws with user mary with force password changed for the first time of login to the platform as analyst.
![user mary force password change](img/step26-analyst-mary-login-with-auto-passwd-changed.jpg)






- Step 27

Screenshot of aws user mary login page trying to test her access to s3 storage bucket that was given access to on the company's platform to be able to create a storage for the company's website database to store data and edit it. She created storage called "production-database" and it is was successful as expected.
![user mary access granted tested](img/step27-analyst-mary-s3-creation-access-active.jpg)





- Step 28

Screenshot of aws user mary login page trying to test her access to s3 storage bucket that was given access to edit and delete it. She deleted "production-database" successful as expected.
![user mary access granted tested](img/step28-analyst-mary-s3-edit-access-active.jpg)





- Step 29

Screenshot of aws user mary login page trying to test her access if it will work on resources that he did not have access to  which is ec2 as it is out of his job purview and he got access denied, when trying to create an instance as expected.
![user mary access denied tested](img/step29-analyst-mary-ec2-creation-access-denied.jpg)



THE PROJECT REFLECTION:


1. Role of IAM in AWS
IAM (Identity and Access Management) is a fundamental AWS service that helps you:
- Securely control access to AWS services and resources.
- Authenticate users and services (who are you? ROLE).
- Authorize actions (what are you allowed to do? PERMISSION).
AWS Process:
- Use IAM to create users, groups, and roles.
- Assign policies to define permissions.
- Monitor access with CloudTrail and IAM Access Analyzer.

2. IAM Users vs. IAM Groups
- IAM User: Represents a single person or application with credentials (username/password or access keys).
- IAM Group: A collection of users with shared permissions.
AWS Process:
- Create a user for each individual (e.g., john, mary) and you can even create the user in a way to differentiate user aside the name like john_dev and mary_analyst.
- Create groups like development Team, Analysts Team, and assign policies to the group.
- Add users to groups to inherit permissions.
Example:
- John (developer) → IAM user in Developers group.
- Mary (analyst) → IAM user in Analysts group.



3. Creating IAM Policies
IAM policies are JSON documents that define what actions are allowed or denied on which resources.
AWS Process:
- Go to IAM > Policies > Create Policy.
- Use the Visual Editor or JSON to define permissions.
- Specify:
- Service (e.g., S3, EC2)
- Actions (e.g., s3:GetObject)
- Resources (e.g., specific bucket)
- Review and create the policy.
- Attach it to a user, group, or role.


4. Principle of Least Privilege
This means only granting the minimum permissions necessary to perform a task.
Why it matters:
- Reduces risk of accidental or malicious misuse.
- Limits the blast radius of compromised credentials.
AWS Practice:
- Start with no permissions.
- Add only what’s needed.
- Regularly audit and refine policies.

5. Scenario: John (Developer) & Mary (Analyst)

IAM Setup Example: 

| Person | IAM User     | Group        | Policy Attached       | Reason    

| John   | john_dev     | Developers   | Full access to EC2    | Needs deploy and manage ec2       

| Mary   | mary_analyst | Analysts     | Full access to S3     | Needs to analyze data and modify it 



Alignment with Least Privilege:
- John can’t access data analytics tools.
- Mary can’t launch or modify EC2 instances.

