[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

Docker Engine Role
===================

Ansible role to install and configure the BLCR checkpointing tool (recipe for EC3)

Example Playbook
----------------
```
  - hosts: server
  roles:
  - { role: 'grycap.blcr', blcr_type_of_node: "front", blcr_install_awscli: "yes"}
```
```
  - hosts: client
  roles:
  - { role: 'grycap.blcr', blcr_type_of_node: "wn"}
```

Contributing to the role
========================
In order to keep the code clean, pushing changes to the master branch has been disabled. If you want to contribute, you have to create a branch, upload your changes and then create a pull request.  
Thanks