Project details
===============
Template was designed by Arun Sanna mail :sanna.arunchowdary@gmail.com
designed from the template from AWS documentation.
Assignment submitted to REAN Cloud

Objective:
==========
Use CM tools such as Puppet, Ansible, or Chef to automate the installation 
1. Basic Drupal or WordPress. 
2.Setup a sample site. 
3.Automate the solution using Cloudformation template.
 
Deliverable:
=============
A cloudformation template that accepts user inputs as parameters where applicable ( for example, Admin password).
This template should setup VPC, create subnets, launch a CM instance, 
pull the necessary code (modules, classes, recipes etc) from a GIT repo (or S3), and configure the web instance for basic Drupal or Wordpress setup.

Configutation
--------------
wordpress server has been created intially.
The template has been updated with the Virtual Private Cloud and Subnet.
VPC Classless Inter Domain Route Address(CIDR) is 10.0.0.0/16 with total 65535 hosts
subnet created inside the VPC with CIDR 10.0.0.0/24 with 256 hosts side a subnet