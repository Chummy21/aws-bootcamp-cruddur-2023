# Week 0 — Billing and Architecture

## Required Homework/Task

First, I started with understanding the Architecture of the Crudder App and the overview of how it looks like. Then, I proceeded to do the following;

### Recreating a Conceptual Diagram in Lucidchart

I recreated the Conceptual Diagram in Lucidchart; 'See image' below;

!['Conceptual Diagram'](assets/Week%200-Crudder%20Conceptual%20Diagram%20(1).png)

[Lucidchart Link](https://lucid.app/lucidchart/867951fc-95ff-491b-aab2-1b22c2b3c19d/edit?viewport_loc=-786%2C-316%2C2549%2C1192%2C0_0&invitationId=inv_faba2d84-4884-4b9c-84cd-034e792fa34f)

### Recreating a Logical Architectural Diagram in Lucidchart

I also worked on recreating the Logical Diagram which includes the actual AWS services to be used; 'See image' below;

!['Logical Diagram](assets/Week%200-Cruddur%20Logical%20Architectural%20Diagram%20(1).png)

[Lucidchart Link](https://lucid.app/lucidchart/c53bae53-3bdc-4476-85af-7086888c3eb6/edit?viewport_loc=-84%2C-45%2C2167%2C1013%2C0_0&invitationId=inv_4cea3189-2a56-4a4b-9e0a-0bce43e2aded)

The next step I took was setting up my cloud environment by doing the following;

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



