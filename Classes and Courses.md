---
bg: "bg.jpg"
layout: page
title: "Classes and Courses"
active: classes
order: 4
---
##### Current Offerings
- [Technology Track: AWS Security - One Day BootCamp](#technology-track-aws-security---one-day-bootcamp)
- [Technology Track: Security in DevOps - One Day BootCamp](#technology-track-security-in-devops---one-day-bootcamp)
##### Upcoming classes
OnRamp / Rapid(re)Start / OT Security / Azure Security / Office 365 Security / Risk Management Framework and CyberSecurity Framework
##### Upcoming Courses
Security Life-cycle  / Security Management / Certifications Prep

## Technology Track: AWS Security - One Day BootCamp
### Industry need
Amazon Web Services (AWS) is a secure cloud services platform, offering computing power, database storage, content delivery and other functionality to help businesses scale and grow. AWS provides secure infrastructure and services, while you, the customer, are responsible for secure operating systems, platforms, and data.
This course will help you in understanding the security at the elevated level and to increase your confidence in securing the AWS environment hand on. Learning of theory is intentionally interspersed with labs on the main topics.
### Course Preview
Interactive learning modules include:
• Creating users
• Assigning roles/privileges
• Key encryption
• Log monitoring
• Log Analysis
• Creating/launching EC2 instances
• Creating S3 buckets
• Conducting compliance based assessment
### Modules
Following the introduction to Cloud Security, Shared Responsibility Model, and Cloud Knowledge bases, the class focuses on the following 5 modules. Most of the learning is in line with hands-on classes.
#### Module 1 Lab
Administration, you will learn how to an on-ramp to AWS. You will work on AWS Console, AWS CLI and create a simple LAMP stack using Cloud Formation. You will create an EC2 machine and gain access to it. You will also setup S3 bucket. To gain access to course you will have to set up users and roles. 
#### Module 2 Lab
The audit, you will audit your own actions done under Module 1 by looking into CloudTrail logs.
#### Module 3 Lab
Build, you will be building Infrastructure as code using CloudFormation and other tools.
#### Module 4 Lab
Test, you will then learn to review CloudFormation as though you are doing a code review. We will use tools such as CloudSploit (basic and introductory) to understand security issues in Infrastructure as Code. We will then walk through a few of the lessons learned by the instructors in working with CloudFormation.
#### Module 5 Lab
You will quickly review a few AWS best practices, understand a few Enterprise considerations (enterprise = multi-cloud + on-prem), and the CIS benchmark.
You will then assess a sample stack using a few of the CIS benchmark checks. You will also understand how to leverage Trusted Advisory and AWS Inspector. As time permits you will look over the reports they produce.
#### Module 6 Lab
Monitoring, Alerting, Auditing, and Incident Response
The lab will cover some of the topics mentioned above to provide you with hands-on training.
By the end of the course, you will have hands-on experience and understanding of AWS and Cloud Security to help you do your job better and perhaps even help accelerate adoption of Cloud at your organization.

## Technology Track: Security in DevOps - One Day BootCamp
### Industry need
DevOps is the evolution of need for speed in software and systems delivery lifecycles. Security is one of the harder non-functional areas to be incorporated into DevOps. This class will teach students the concepts of integrating Enterprise processes with security processes with Automation in mind. Students will then get to automate a few of the DevSecOps security steps within a Jenkins reference pipeline. Though not a pre-requisite, we recommend leveraging our OnRamp to IT security offering to get the most out of this class in terms of automation understanding. The AWS Security class will also add value to this class during hands-on exercises.  
### Course Preview
Our newest course builds on the skills learned in our previous classes yet introducing you to the software development lifecycle and the unique security threats that it presents. You will have more hands-on experience with our cutting edge AWS cloud technologies while learning about specific DevSec tools such as the Jenkins reference pipeline.
### Modules
#### Module 1
What is DevOps? What are the security concerns of DevOps? When and how to check if these concerns can materialize? How to assess the size of the impact if these concerns materialize?
#### Module 2
Understand and execute tasks from an Orchestration Engine used in DevOps. Understand issues with each of shell scripts, plug-ins, and loosely coupled invocation of security tools.
#### Module 2 Lab
Learn Jenkins navigation – and the brief overview of its orchestration ability
Create a job, configure a job to invoke a batch file, run the job, review the outputs, create logic based on output data, and invoke the next job
#### Module 3
Understand and execute code review
#### Module 3 Lab
##### Sample code review
Review a sample Python application, understand a few code vulnerabilities, understand and run Python Bandit code review tool, review the output, pipe the results back into Jenkins, automate the processing of some of the vulnerabilities data, invoke or abort next job based on the results
#### Module 4
Understand issues caused by third-party libraries. Understand issues caused due to issues with your supply chain
#### Module 4 Lab
##### Sample libraries review
Review a sample application, understand a few vulnerabilities due to insecure third-party libraries in it, understand and run OWASP Dependency check tool to discover all other vulnerabilities (CVEs), review the output, pipe the results back into Jenkins, automate the processing of some of the vulnerabilities data, invoke or abort
#### Module 5
Understand issues with automatic provisioning of infrastructure (NW, OS, stacks, containers, pods, etc.) that will host your application. Understand infrastructure as code security concerns
#### Module 5 Lab
##### Infrastructure review
Review a sample infrastructure; use automatic scripts discovery of a few vulnerabilities in one or more of infrastructure as code, NW, OS, files and directories, and containers (time permitting); review the output; pipe the results back into Jenkins; automate processing of some of the vulnerabilities data; invoke or abort next job based on the results
#### Module 6
Understand issues with web applications. Understand the impact of such issues on business and data.
#### Module 6 Lab
##### Dynamics scans
Review a sample vulnerable python web application; use automatic scan of the application using OWASP ZAP; invoke ZAP as a GUI, via command line invocation, via APIs, and via Jenkins plugin; review the output; pipe the results back into Jenkins; automate processing of some of the vulnerabilities data; invoke or abort next job based on the results


## Technology Track: Security in DevOps - One Day BootCamp
### Industry need
Industrial Control Systems (ICS) operate the technology needed for our Critical Infrastructures such as Transportation, Manufacturing. Etc. This class brings students closer to understanding the security implication of OT Security. Though not a pre-requisite, we recommend leveraging our OnRamp to IT security offering to get the most out of this class. The AWS Security class will also add value to this class during hands-on exercises. 
This course will help you in understanding the security at a high level and to gain your confidence in securing the AWS environment interspersed with labs on the main topics.
### Course Preview
Industrial Control Systems (ICS) operate the technology needed for our Critical Infrastructures such as Transportation, Manufacturing. Etc. This class brings students closer to understanding the security implication of OT Security. Though not a pre-requisite, we recommend leveraging our OnRamp to IT security offering to get the most out of this class. The AWS Security class will also add value to this class during hands-on exercises. 
#### Module 1
In our first module, we will discuss the key differences between IT and OT in terms of function and security. After we have identified the major differences we will introduce you to the IEC62443 standard and the Purdue Reference Model, both of which act as a guideline for merging your enterprise and industrial networks, while minimizing the risk of vulnerabilities. Then we will introduce you to the Department of Homeland Security's Cyber Security Evaluation Tool (often referred to as CSET).
#### Module 2
In module two we will introduce you to Programmable Logic Controllers, ladder logic, and common OT protocols. Once we have become familiar with how PLC’s work and their components, we will walk you through the setup of a Siemens S7 12007 PLC. Once it is operational we will then walk you through the installation of the S7/TIA software.
#### Module 3
In module three we will discuss what possible security flaws may have been created in the setup module. We will also discuss common security concerns that are unique to OT and PLC’s in general, including inventory development, identity issues, password management, patch management, network footprint, logs and log aggregation, etc. After discussion, we will attempt to look at what we set up in module 2 and audit it for the above concerns.
#### Module 4
In our next activity, we will discuss the protocols and other factors that allow devices in an OT system to communicate. You will learn about the Internet of Things and Industrial Internet of Things (IoT&IIoT). You will then get devices such as a fan, light, sensor, or actuator programmed and communicating with our Siemens PLC and demonstrate how Modbus enables the devices to communicate. We will then explore the internet accessibility of the PLC and see how the IoT adds a new challenge to security.
#### Module 5
Now that we understand the concepts of OT, we will look at how vulnerabilities are exploited and thwarted in the Industrial Controls Systems sector. First we will start by conducting a simple Denial of Service attack on a PLC using OWASP Zed Attack Proxy to shut it down with a flood of HTTP requests, next we Will show you how to use the Python programming language to create a simple yet crippling attack on the Modbus protocol of the PLC, and last but not least we will learn about using NMAP to conduct a port scan on the PLC.
#### Module 6
Now that we know how to force our way into OT networks and wreak havoc, we will so you how to prevent attacks and stay up to date on vulnerabilities in the ever-changing landscape of Critical Infrastructure. We will start by introducing you to Intrusion Detection and Intrusion Prevention systems and how they work, next we will set up an actual Intrusion Detection System from Radiflow.
Once the IDS is working we will gather some network traffic data and transfer it to the NSA’s GrassMarlin tool and analyze traffic and identify network assets. Once a comprehensive set of data has been gathered we will then conduct an asset-based cybersecurity assessment using the DHS’ Cyber Security Evaluation Tool.
Next, you will become familiar with NERC and CIP controls that dictate necessary security measures for Industrial Control Systems. You will then learn about some cool tools such as Splunk which can provide near-real-time continuous network monitoring. 
