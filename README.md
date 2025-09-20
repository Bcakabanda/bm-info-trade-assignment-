Azure Cloud & Data Engineering Project

Overview
This project demonstrates key skills in cloud computing and data engineering, specifically using Microsoft Azure. The goal was to configure a complete working environment, including a virtual machine, a web server integrated with Apache Spark, and a functional webpage hosting. Additionally, a basic Active Directory setup was implemented for user management demonstration.

This assignment was given by a company as a hands-on task to evaluate practical skills in cloud infrastructure and data processing.

Key Features
Virtual Machine Setup: Creation and configuration of a Linux virtual machine on Microsoft Azure.

Web Server: Installation and configuration of a web server with use of apache on the VM.

Spark Integration: Installation of Apache Spark and its integration with the web server for data processing tasks.

Webpage Hosting: Deployment of a simple webpage on the web server to demonstrate successful hosting.

Active Directory Demo: A proof-of-concept setup for user and group management using Azure Active Directory (now Microsoft Entra ID).

Technologies Used
Cloud Platform: Microsoft Azure

Data Processing: Apache Spark

Operating System: Linux (e.g., Ubuntu, CentOS)

Web Server: Apache/Nginx (specify which one you used)

Scripting: Shell scripting (e.g., Bash)


Azure Setup:

Create a resource group in your Azure subscription of student 1 month free trial 

Deploy a new virtual machine.

VM Configuration:

Connect to the VM via SSH.

Run the following commands to install the web server and Spark: 
sudo apt update
sudo apt install apache2 -y
sudo systemctl start apache2


Hosting:

Copy the webpage files to the web server's directory (/var/www/html).

Set up network security groups (NSGs) to allow web traffic (port 80/443).

