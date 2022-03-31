packageManager
=========

packageManager role will deploy the keys, repos and packages necessaries to debian or fedora hosts

Requirements
------------

Ansible 2.9 or above

Role Variables
--------------

```
List of keys: 
  debian_keys: []
  fedora_keys: []

List of repositories:
  debian_repositories: []
  fedora_repositories: []

list of packages:
  debian_packages: []
  fedora_packages: []
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
