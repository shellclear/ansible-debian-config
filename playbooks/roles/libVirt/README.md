libVirt
=========

libVirt role will deploy libvirt resources, pools, domains and networks and also is able to make backups of that resources generating xml files and save then inside role/files folder.

Requirements
------------

Ansible 2.9 or above

Role Variables
--------------

```
List of pools: 
  pools: []

```

Dependencies
------------

No dependencies

Example Playbook
----------------

```
- hosts: all
  roles:
    - libVirt
```

License
-------

BSD

Author Information
------------------

shellclear
