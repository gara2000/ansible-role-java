Java
=========

This role installs Java on remote server

Requirements
------------

- Ubuntu 22 or Ubuntu 24

Role Variables
--------------

- No variables

Dependencies
------------

- No dependencies 

Example Playbook
----------------
```bash
- hosts: servers
  become: yes
  roles:
      - gara2000.java
```

License
-------

BSD