# Day 7
## Prompt
During the weekly meeting, the Nautilus DevOps team discussed about the automation and configuration management solutions that they want to implement. While considering several options, the team has decided to go with Ansible for now due to its simple setup and minimal pre-requisites. The team wanted to start testing using Ansible, so they have decided to use jump host as an Ansible controller to test different kind of tasks on rest of the servers.

Install ansible version 4.9.0 on Jump host using pip3 only. Make sure Ansible binary is available globally on this system, i.e all users on this system are able to run Ansible commands.

---

## My Solution

1. Had to do some research on options for ansible install for versions and how to install for all users. Found that you have to install with sudo to enable for all users and version can be chosen by adding ==x.x.x after the ansible tag.
2. For installation I ran ```sudo python3 -m pip install ansible==4.9.0```
3. To check that ansible is available to other users, I used the command ```whereis ansible``` to make sure it was installed in the ```/usr/local/bin``` directory for all users to access.
4. SUCCESS!