andrewrothstein.getenvoy
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-getenvoy.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-getenvoy)

Installs [GetEnvoy](https://github.com/tetratelabs/getenvoy) by Tetrate Labs

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
    - andrewrothstein.getenvoy
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
