Emby
=========

[![Build Status](https://travis-ci.org/maxlareo/ansible-emby.svg?branch=master)](https://travis-ci.org/maxlareo/ansible-emby) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-emby-blue.svg)](https://galaxy.ansible.com/maxlareo/emby/)

An Ansible role that installs Emby (https://emby.media/).

Role Variables
--------------

- `emby_user`: [default: `emby`]
- `emby_group`: [default: `emby`] 
- `emby_dir`: [default: `/usr/lib/emby-server`]
- `emby_bin`: [default: `/usr/lib/emby-server/bin/MediaBrowser.Server.Mono.exe`]
- `emby_data`: [default: `/var/lib/emby-server`]
- `emby_pidfile`: [default: `/var/run/emby-server.pid`]
- `emby_add_opts`: [default: `''`]
- `mono_bin`: [default: `/usr/bin/mono-sgen`]
- `mono_opts`: [default: `--optimize=all`]
- `mono_env`: [default: `MONO_THREADS_PER_CPU=500 max-heap-size=96m,soft-heap-limit=64m,nursery-size=4m`]

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
