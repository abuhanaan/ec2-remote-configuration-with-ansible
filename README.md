# Remote Control Using Ansible
This repository is targetted at building a playbook that automates configuration of an EC2 instance by [adapting manual](https://www.howtoforge.com/tutorial/nodejs-ubuntu-getting-started/) instructions to Ansible Playbook tasks.

## Pre-requisite
* Key pair - associated to an AWS EC2 key pair already created on AWS Console. For the scope of this exercise, the key pair name is udacity.pem.
* EC2 instance - An AWS EC2 Ubuntu instance mapped with the udacity.pem key-pair currently running on my AWS account. The property:value tag Project:udacity is associated to the instance.
* Inventory file - The inventory file containing the public IP address of my AWS EC2 Ubuntu VM.
    * The bash file getTarget.sh is run to get the public IP address associated to the EC2 instance saved into the inventory file.
