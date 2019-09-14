ansible_epel
=========

Role is intended to install and configure EPEL repository on a Red Hat server.

Requirements
------------

_Optional:_ Run it with sudo password prompt:
```
ansible-playbook --ask-become-pass main.yml -l remote
BECOME password: 
```

Role Variables
--------------

No variables.

Dependencies
------------

No dependencies.

Example Playbook
----------------

An example of how to use your role:

    - hosts: servers
      become: yes
      roles:
         - ansible_epel

License
-------

BSD

Author Information
------------------

> https://github.com/110marc
