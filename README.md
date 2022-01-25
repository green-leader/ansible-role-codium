Role Name
=========

Install [Codium](https://vscodium.com/) a community-driven, freely-licensed binary distribution of Microsoft’s editor VSCode.

Requirements
------------

None.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```yml
    - hosts: workstations
      roles:
         - { role: green_leader.codium, become: yes }
```

License
-------

MIT
