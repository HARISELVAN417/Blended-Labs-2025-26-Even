# Lab 6 – Scale and Load Balance Your Architecture
## Name : HARISELVAN S
## Reg No : 212224040103
## Title

Scale and Load Balance Your Architecture
Author : your name   Reg no : yours   Date :

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

1.Logged in to the AWS Management Console and reviewed the existing EC2 web server.

2.Created an AMI, target group and Application Load Balancer.

3.Created a launch template and configured an Auto Scaling Group.

4.Attached the Auto Scaling Group to the load balancer and configured a CPU-based scaling policy using CloudWatch.

5.Generated traffic, verified automatic scaling from 2 to 4 healthy instances, terminated the original web server and submitted the lab.

## Output Screenshots 
<img width="1906" height="972" alt="Screenshot 2026-11-25 135915" src="https://github.com/user-attachments/assets/b7a0eafd-87ec-4f29-a6f6-757ecb12aa92" />

<img width="1906" height="972" alt="Screenshot 2026-11-25 135915" src="https://github.com/user-attachments/assets/0164eac9-2f78-40f7-b764-81cbc3edfac3" />

<img width="1903" height="982" alt="Screenshot 2026-11-25 140215" src="https://github.com/user-attachments/assets/92fe1fd9-347a-4bc0-9296-3ba04c6a0dee" />

<img width="1907" height="970" alt="Screenshot 2026-11-25 140507" src="https://github.com/user-attachments/assets/9afcec17-0a34-4f06-8f58-06d9de793215" />

<img width="1907" height="939" alt="Screenshot 2026-11-25 141206" src="https://github.com/user-attachments/assets/bfe4194a-5205-42c3-9cd6-952ffe86f21f" />

<img width="1907" height="961" alt="Screenshot 2026-11-25 144353" src="https://github.com/user-attachments/assets/08afa9f9-7343-4347-8f5f-c80dc7cd0439" />

## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
