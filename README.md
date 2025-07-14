Ansible role update
=========

An Ansible role that installs updates and reboots the host if required.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  become: true
  roles:
     - cesargoncalves.update 
```

License
-------

GPL-3.0

Author Information
------------------

Role created by [cesargoncalves](https://github.com/cesargoncalves)
