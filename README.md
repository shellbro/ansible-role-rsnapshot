rsnapshot
=========

Ansible role for building a backup server (CentOS 7).

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
