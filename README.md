# Elastic Web Service Implementation

## Overview
This document outlines the steps taken by Md Hasibul Haque Zahid (ID: 2302302) to implement an elastic web service using AWS.

## Steps Taken

### 1. EC2 Instance Creation
- **Launched a new EC2 instance** using the AWS Management Console.
- Selected the instance type, network configuration, and Amazon Linux 2 OS

### 2. Instance Access
- Accessed the instance via SSH using the command `ssh -i my-key.pem ec2-user@<instance-public-ip>`

### 3. PHP Setup
- Installed PHP and necessary dependencies on the Amazon Linux instance using `sudo yum install php`.

### 4. HTTPS Certificate Installation
- Secured the web service with an SSL/TLS certificate from Let's Encrypt.
- Configured the web server for HTTPS communication.

### 5. Web Service Configuration
- Moved PHP application files to the server directory.
- Edited server configuration files to set up the document root and server options.

## Load Testing
Performed load testing using `httperf` with various sessions and rates to create load on the instances.

## Auto-Scaling Analysis
Detailed analysis of the auto-scaling mechanism's behavior and reactivity to load variations, including increased and decreased load scenarios.

## Applications Benefitting from Auto-Scaling
- E-commerce platforms like AliBaba during peak seasons.
- Streaming services like Netflix for fluctuating demand.
- Social media platforms like Facebook for viral content.
- Online gaming platforms like Steam for varying player numbers.

## Reflection
Insights into the implementation and management of a web service on AWS, focusing on auto-scaling mechanisms and load balancer integration.

## Report
I have also written a detailed report based on these Project. The report provides a comprehensive overview of the Project.For more information, please refer to the report.

## Video Demonstration
A video link is provided to showcase the implementation process.

## Contact
If you have any questions or would like to discuss the project further, feel free to reach out to me.
