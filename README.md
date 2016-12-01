Ansible Role - xCAT Repository
==============================

Installs [xCAT][] package repository.

Requirements
------------

Currently supports only RHEL/CentOS.

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
    - { role: repo-xcat, tags: ['xcat'] }
```

License
-------

MIT

[xCAT]: http://xcat.org/
