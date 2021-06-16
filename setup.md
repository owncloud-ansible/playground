---
title: Setup
---

These docs are work in progress so they will be incomplete. 

Current required Ansible version is minimum 2.10 or higher on all Linux distribution.

Install a newer Ansible version like:

`python3 -m venv ~/ansible && source ~/ansible/bin/activate && pip3 install ansible`

## CentOS 7 
### Requirements
These are the packages / repositories that need to be enabled / installed before the first playbook execution.

- Software Collections enabled: 
`yum install centos-release-scl`
- EPEL enabled: 
`yum install epel-release`
- GCC installed: 
`yum install gcc`
