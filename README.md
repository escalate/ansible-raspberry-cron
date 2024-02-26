[![Test](https://github.com/escalate/ansible-raspberry-cron/actions/workflows/test.yml/badge.svg?branch=master&event=push)](https://github.com/escalate/ansible-raspberry-cron/actions/workflows/test.yml)

# Ansible Role: Raspberry - Cron

An Ansible role that manages [cron](https://wiki.debian.org/cron) on Raspberry Pi OS (Debian Bookworm).

## Role Variables

This roles has no variables that can be overridden.

## Dependencies

This role relies on the following dependencies:

* Roles: None
* Collections: None

## Installation

```
$ ansible-galaxy role install escalate.cron
```

## Example Playbook

```
- hosts: all
  roles:
    - role: escalate.cron
      tags: cron
```

## License

MIT
