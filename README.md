# Ansible Role: Conky

[![CI](https://github.com/djonasson/ansible-role-conky/workflows/CI/badge.svg?event=push)](https://github.com/djonasson/ansible-role-conky/actions?query=workflow%3ACI) [![Ansible Galaxy Quality Score](https://img.shields.io/ansible/quality/57604)](https://galaxy.ansible.com/djonasson/conky/) [![Ansible Galaxy](https://img.shields.io/ansible/role/d/57604)](https://galaxy.ansible.com/djonasson/conky/) [![MIT Licence](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/djonasson/ansible-role-conky/blob/main/LICENSE)

Ansible role for installing conky and download the configuration from a git repository.

## Requirements

Requires `git` on the managed machine.


## Role Variables

The role variables are defined in `defaults/main.yml` with these defaults:

    repo: "https://github.com/djonasson/conky-config.git"
    dest: "~/.conky"
    version: master
    accept_hostkey: false

## Dependencies

None

## Example Playbook

    - hosts: localhost
      roles:
        - role: djonasson.conky

## License

MIT

## Author

This ansible role was created by [Daniel Jonasson](https://github.com/djonasson/).
