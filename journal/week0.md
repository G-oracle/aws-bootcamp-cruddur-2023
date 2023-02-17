# Week 0 — Billing and Architecture

## Required Homework/Tasks

    I started out with understanding of the Cruddur App Architecture to have an overview of what the App looks like. I proceeded to doing the following

### **Recreate Conceptual Diagram in Lucid Charts**

I designed the Conceptual Diagram on Lucid Charts, `see image` below

!['Conceptual Diagram'](/_docs/week_0/Week_0-Billing_and_Architecture-Conceptual_Diagram.png)

[Lucid Charts Share Link](https://lucid.app/lucidchart/6f7627c3-f57c-4940-8983-48fbb14fd30d/edit?viewport_loc=-234%2C-34%2C2204%2C1060%2C0_0&invitationId=inv_9c3b6aa2-b321-4e8b-81c0-5a93bdb0796e
)

### **Recreate Logical Architectual Diagram in Lucid Charts**

I also worked on recreating the logical Diagram which includes the actual AWS Services to be used, `see image` below

!['Logical Diagram'](/_docs/week_0/Week_0-Billing_and_Architecture%20-Logical_Diagram.png)

[Lucid Charts Share Link](https://lucid.app/lucidchart/6f7627c3-f57c-4940-8983-48fbb14fd30d/edit?viewport_loc=494%2C1252%2C2204%2C1060%2CqGTxC2gO0-Zj&invitationId=inv_9c3b6aa2-b321-4e8b-81c0-5a93bdb0796e
)


    Next, I made sure in getting my cloud environment set up. The basic cloud environment setup I did is as follows:

### **Create an Admin User**

- I already have an `Admin User` created on my AWS account with `CLI privileges` called `CLI-Admin` (see image below).

![Admin User](/_docs/week_0/Admin_User.png)

- I also have `AWS CLI` installed (check this [article](https://medium.com/aws-in-plain-english/how-to-launch-an-ec2-instance-in-aws-15db3b22101d) for the installation process on ***Ubuntu***)

![AWS CLI](/_docs/week_0/AWS_CLI.png)



### Create a Budget and Billing Alarm

I created my own Budget for `$100` because I cannot afford any kind of spend.
I did not create a second Budget because I was concerned of budget spending going over the `2` budget free limit.

![Budget](/_docs/week_0/budget.png)

I also created an Alarm for the budget when it reaches a threshold of `80%`

![Billing Alarm](/_docs/week_0/Billing_Alarm.png)

### Added CLI-Admin Credentials to Gitpod Environment Variables

![Gitpod Variables](/_docs/week_0/gitpod.png)
