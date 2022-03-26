Role Name
=========

PackageManager role will deploy the keys, repos and packages necessaries to debian or fedora hosts

Requirements
------------

Ansible 2.9 or above

Role Variables
--------------

```
List of keys: 
  keys:
    debian: []
    fedora: []

List of repositories:
  repositories:
    debian: []
    fedora: []

list of packages:
  packages:
    debian: []
    fedora: []
```

Dependencies
------------

No dependencies

Example Playbook
----------------

```
- hosts: all
  roles:
    - packageManager
```

License
-------

BSD

Author Information
------------------

shellclear