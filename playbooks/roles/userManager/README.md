userManager
=========

userManager role will deploy the users and groups to debian or fedora hosts

Requirements
------------

Ansible 2.9 or above

Role Variables
--------------

```
List of users: 
  debian_users: []
  fedora_users: []
```

Dependencies
------------

No dependencies

Example Playbook
----------------

```
- hosts: all
  roles:
    - userManager
```

License
-------

BSD

Author Information
------------------

shellclear
