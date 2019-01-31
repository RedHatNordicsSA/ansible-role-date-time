ansible-role-date-time
======================

Installs chrony for time keeping for server.

Requirements
------------

Server must work with chrony.

Role Variables
--------------

There is list of variables in defaults/main.yml which can be overridden in
vault or in Tower. You may need to modify them to use this role.

Dependencies
------------

No dependencies

Example Playbook
----------------

- include_role:
    name: ansible-role-date-time

License
-------

BSD

Author Information
------------------

Peter Gustafsson, pgustafs@redhat.com
[Red Hat](https://redhatnordicssa.github.io/)
