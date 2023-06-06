[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

freeradius
==========


Installs FreeRADIUS

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

freeradius_template: radiusd.conf.j2

Dependencies
------------

None

Example Playbook
----------------

Install FreeRADIUS
```yaml
- hosts: all
  roles:
    - m5run.freeradius
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
