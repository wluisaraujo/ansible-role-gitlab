[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-gitlab.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-gitlab) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-GitLab-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-gitlab)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Gitlab SCM](https://gitlab.com)
------------

Description
------------

 *

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars_files:
    - vars/main.yml
  vars:
    - gitlab_external_url: "http://gitlab.example.com" 
  roles:
    - iac-ansible-gitlab
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
