AnsibleRoleOsLinuxUpgrade
=========

This role will upgrade all Apt or Yum packages to newest available version.
In case of Debian based operating system role will also remove all unused or unnecessary files.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

This role depends on role kamikazestar.AnsibleRoleOsLinuxUpdate.

Example Playbook
----------------

Below ther's example playbook which can be used:

    - hosts: servers
      roles:
         - { role: kamikazestar.AnsibleRoleOsLinuxUpgrade }

License
-------

MIT

Author Information
------------------

[Marcin Slabonski](https://github.com/kamikazestar)
