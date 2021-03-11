# Changelog

## [v1.0] - 10-03-2021

### Ansible Roles added for

- Linux vm deployment
- GuestOS customization
- Package installation
- Linux vm deletion

### Software support

- ansible-2.10.6
- pyvmomi-7.0.1

## Deployment Guide:

### To deploy the Web Server, use the below command:

  $ ansible-playbook -i inventory linwebvm.yaml --tags "deploy"

### To do the guest os customization, use the below command:

  $ ansible-playbook -i inventory linwebvm.yaml --tags "oscustom"

### To install the packages, use the below command:

  $ ansible-playbook -i inventory linwebvm.yaml --tags "package"

### To delete the Web Server use the below command:

  $ ansible-playbook -i inventory linwebvm.yaml --tags "delete"

