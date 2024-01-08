# Ansible install Jenkins on Ubuntu 22.04
Ansible playbook to install a Jenkins server using ssh.

Command for execute playbook: 

    ansible-playbook -i 192.168.0.X, -u root --extra-vars ansible_ssh_pass=Password123 ansible-install-jenkins-ubuntu22.yml

## Description: 

You will need to configuree the host `192.168.0.X` the user `root` and password `Password123` with your target
server credentials.

## Infos:

__Target OS:__ Ubuntu 22.04

