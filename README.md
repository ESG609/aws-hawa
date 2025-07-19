# AWS-HAWA
Documentation for a Highly Available Web Application hosted on EC2 Load Balancers and Auto Scaling Groups

Project Overview

- In this Project, I have built a highly available web application architecture using Amazon Web Services (AWS). The goal was to create a scaleable system that can handle varying loads and remain accessible even if inidividual components fail.

Key services:
- EC2 Instances: Virutal servers running our web application
- Application Load Balancers (ALB): Distributes incoming traffic across multiple EC2 instances
- Auto Scaling Group: Automatically adjusts the number of EC2 instances based on demand (When a server shuts down or eccess netowrking trafficing)
- Launch Template: Defines teh condifuration for new EC2 instances

Step by Step Process:
Creating a EC2 Instance

