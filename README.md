# Ansible Playground

This repository is intended as an entry point into an ownCloud deployment with Ansible and will also act as a showcase and documentation for possible deployment trategies.

# Testing

## Testing using Vagrant

Vagrant makes it possible to run Ansible scripts inside a virtual machine (backed by VirtualBox).

- For the first time setup, please run `vagrant up`.
- Then after making changes to the playbooks, roles or inventory, please run `vagrant provision` to apply the changes to the virtual machine.
- The deployed ownCloud instance is accessible under http://172.30.1.2/ with user "admin" and password "owncloud".
- The command `vagrant ssh` makes it possible to enter the VM for debugging purposes.

