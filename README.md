Ansible Role - xCAT Repository
==============================

[![Build Status](https://travis-ci.org/idiv-biodiversity/ansible-role-repo-xcat.svg?branch=master)](https://travis-ci.org/idiv-biodiversity/ansible-role-repo-xcat)

Installs [xCAT][] package repository.

Requirements
------------

Supports:

- RHEL / CentOS
- Ubuntu

Role Variables
--------------

-   **xcat_version**

    default: *latest*

Dependencies
------------

None.

Example Playbook
----------------

```yml
- name: xcat image provider
  hosts: servers
  vars:
    xcat_version: "2.10"
  roles:
    - role: repo-xcat
      tags:
        - xcat
```

License
-------

MIT

[xCAT]: http://xcat.org/
