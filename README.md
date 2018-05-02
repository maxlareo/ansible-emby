Emby
=========

[![Build Status](https://travis-ci.org/maxlareo/ansible-emby.svg?branch=master)](https://travis-ci.org/maxlareo/ ansible-emby) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-emby-blue.svg)](https://galaxy.ansible.com/maxlareo/emby/)

An Ansible role that installs Emby (https://emby.media/).

Requirements
------------

None

Role Variables
--------------

- `emby_user`: [default: `emby`]
- `emby_group`: [default: `emby`] 

Dependencies
------------

None

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - emby
```

License
-------

MIT

Author Information
------------------

[Maxime Lareo](https://github.com/maxlareo)

Feedback, bug-reports, requests, ...
------------------------------------

Are [welcome](https://github.com/maxlareo/ansible-emby/issues)!
