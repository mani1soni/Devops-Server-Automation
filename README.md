# Devops-Server-Automation
The Server Automation is created by devops automation tool like Ansible. The Source code of
ansible is written in python. It is highly usable automation tool. We also make a cluster file
system. We implement it by GlusterFS software. Basically our project is containing four major
parts. First one is Automated Cluster File system & Software installation, A File Server,
Netboot Pre-execution environment and Dynamic Integrated Development Environment (IDE).
We use devops technology to implement this project. DevOps is a collaboration of development
and operations devised to stress on communication and integration between them. The main of
DevOps is to help an organization to grow and excel. With its help an organization can produce
software products and services. The main use of DevOps is to streamline the day to day activities
of an organization and speed up the process for timely deliveries.
The Devops server automation is very giant project. The main aim of this project is to improve
the infrastructure of our college‘s computer labs.

## Plateform Used: Linux / Ubuntu*
## Install Ansible:
sudo apt-get install ansible -y

## Create Two Virtual Machines or use two different systems for cluster server and one separate
Run Playbook1 files for automated ssh authorization for machines.
like:- ansible-playbook server.yml -u gfs1(Machine name) --ask-become-pass (For Sudo Access)

Then Run Second Ansible Playbook For Glusterfs-Server And Glusterfs-Client Installation.

## Team
* [Manish Soni](https://www.linkedin.com/in/manisomanish/)
* [Jaydeep Godara](https://www.linkedin.com/in/jaydeep-godara/)
* [Astha Sharma](https://www.linkedin.com/in/astha-sharma-81b274148/)
* [Jaydeep Godara](https://www.linkedin.com/in/manish-sirvi/)







