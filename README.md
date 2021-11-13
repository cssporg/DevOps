# Project Title
This project is intended to touch and feel DevOps flow

# Pre-Requisites
Step 0: Launch ec2 instance to run terraform with name sandbox

Login to sandbox instance

$sudo yum install git -y

$git clone https://github.com/cssporg/webapp.git

$cd webapp

$sh sandbox.sh

$source export.sh


# DevStack 

Step 1: Build Custom AMI with Packer

https://github.com/devstackorg/packer.git

Step 2: Provision infrastructure with terraform

https://github.com/devstackorg/terraform.git

Step 3: Install and configure softwares using Ansible

https://github.com/devstackorg/ansible.git


# OpsStack
https://github.com/opstacksorg
