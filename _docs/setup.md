---
title: Setup
---

These docs are work in progress so they will be incomplete.

## General

The current required Ansible min version is 2.10 on all Linux distribution. To install latest Ansible version with PIP use:

```Shell
python3 -m venv ~/ansible
source ~/ansible/bin/activate
pip3 install ansible
```

## CentOS 7

### Requirements

These are the packages / repositories that need to be enabled / installed before the first playbook execution.

- Software Collections enabled:
  `yum install centos-release-scl`
- EPEL enabled:
  `yum install epel-release`
- GCC installed:
  `yum install gcc`
