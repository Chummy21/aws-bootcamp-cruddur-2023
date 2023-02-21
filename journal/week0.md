# Week 0 — Billing and Architecture

## Required Homework/Task - Building a Micro-Blogging Platform Called Cruddur

First, I started with understanding the Architecture of the Crudder App, its requirements, features, target audience, cost and the general overview of how the app looks like. Then, I proceeded to do the following;

### Napkin design of the cruddur app

I designed on a napkin a conceptual diagram of the cruddur micro blogging app

!['Napkin Design'](assets/Week%200-%20Napkin%20design.jpg)

### Recreating a Logical Architectural Diagram in Lucidchart

I also worked on recreating the Logical Diagram which includes the actual AWS services to be used; 'See image' below;

!['Logical Diagram](assets/Week%200-Cruddur%20Logical%20Architectural%20Diagram%20(1).png)

[Lucidchart Link](https://lucid.app/lucidchart/c53bae53-3bdc-4476-85af-7086888c3eb6/edit?viewport_loc=-84%2C-45%2C2167%2C1013%2C0_0&invitationId=inv_4cea3189-2a56-4a4b-9e0a-0bce43e2aded)

The next step I took was setting up my cloud environment by doing the following;

### Generate AWS Credentials for the Admin user I created

I created an generated AWS credentials for IAM admin user and also assigned admin access as shown below;

![Generate AWS Credentials](assets/Week%200-Generate%20credentials.PNG)

### Installed AWS CLI

 I installed the AWS CLI via the gitpod environment and confirmed it using the 'aws sts get-caller-identity' command as shown below; 
 
 ![AWS CLI](assets/Week%200-Configured%20the%20AWS%20CLI%20Via%20gitpod%20Environment.PNG)
 
 ### Create an Admin User
 
 I created an Admin User, added the user to a group, assigned permission, enabled multifactor authentication and also granted user administrative access as shown below;
 
 ![Create an Admin User](assets/Week%200-Image%20of%20Admin%20User.PNG)

### Create a Budget 

I created a zero budget for $1 because I cannot afford any kind of spend. I did not create a second budget because I was concerned of budget spending going over the two budget free limit.

![Create a Budget](assets/Week%200-Create%20a%20budget.PNG)

### Create a Billing Alarm

I also setup a billing alarm using the Advanced option (credit) incase I get some credits, to alert me when I exceed my actual spend through email notification.

![Create a Billing Alarm](assets/Week%200-Create%20a%20Billing%20Alarm.PNG)

### I watched Chirag's week 0 spend considerations

I learnt how to track and monitor spend and how to utilize the free tier. I also learnt how to manage billing alert.

### Homework Challenges
'
I could not Launch the cloud shell because it was bringing up an error message so I sent a mail to the AWS support team. I'm still waiting for their response.
