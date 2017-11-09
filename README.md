rsnapshot
=========

[![Build Status](https://travis-ci.org/shellbro/ansible-role-rsnapshot.svg?branch=master)](https://travis-ci.org/shellbro/ansible-role-rsnapshot)

Ansible role to setup a backup server using rsnapshot (CentOS 7).

Requirements
------------

None

Role Variables
--------------

- snapshot_root
- no_create_root
- backup_levels
- backup_points

Dependencies
------------

- shellbro.epel

Example Playbook
----------------

    - hosts: servers
      roles:
        - rsnapshot

License
-------

BSD

Author Information
------------------

Jakub Gorczyca
