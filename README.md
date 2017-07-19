andrewrothstein.sudoers
===========================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-sudoers.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-sudoers)

A role for allowing sudo usage sans password

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.sudoers
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
