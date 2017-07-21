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

Author Information
------------------

This role was created in 2016 by [Christian Krause][author] aka [wookietreiber at GitHub][wookietreiber], HPC cluster systems administrator at the [German Centre for Integrative Biodiversity Research (iDiv)][idiv].


[author]: https://www.idiv.de/groups_and_people/employees/details/eshow/krause-christian.html
[idiv]: https://www.idiv.de/
[wookietreiber]: https://github.com/wookietreiber
[xCAT]: http://xcat.org/
