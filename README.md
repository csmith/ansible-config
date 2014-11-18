Ansible config
===============================================================================

This repo contains the ansible playbooks and config used to provision my own
servers.

Most of the interesting stuff is found in the roles contained in the
[DMDirc/ansible-roles](https://github.com/DMDirc/ansible-roles) repo.

To run all of the playbooks:

    ansible-playbook -i inventories/inventory.yml -u root playbooks/all.yml
