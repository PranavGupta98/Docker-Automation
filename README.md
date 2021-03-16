# Docker-Automation
Description of the Project
In this project I have created an Ansible playbook to automate the following tasks:
1.	Configure Docker 
2.	Start and Enable Docker Services
3.	Pulling the HTTP server image from Docker Hub
4.	Running the Docker Container and configuring HTTP server
5.	Making the HTML file public

In the Controller Node(CN) run this Ansible playbook to configure yum, httpd, python and docker on the Target Node(TN). Include the IP Address of the TN in the inventory file, so we add the IP Address, username and password of the TN.

Harnessing the true power of Ansible which automates these redundant and time taking processes with a single click! This Ansible playbook can configure and setup a Webserver on Container on a fresh RHEL8 Linux system.
