OS Update
=========

This is an Ansible role that updates the Debian Linux.

It runs "apt update" and "apt upgrade".

Requirements
------------

- Ansible >= 2.10

Role Variables
--------------

none

Dependencies
------------

none

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: os_update

License
-------

MIT

Author Information
------------------

Tamas Molnar - <tmolnar0831@gmail.com> - https://tomsitcafe.com
