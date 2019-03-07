[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-gitlab.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-gitlab)
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
  vars:
    - name: value
  roles:
    - iac-ansible-gitlab
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
