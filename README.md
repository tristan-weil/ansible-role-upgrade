# Ansible Role: upgrade

An Ansible Role to upgrade the system and the packages.

[![Actions Status](https://github.com/tristan-weil/ansible-role-upgrade/workflows/molecule/badge.svg?branch=master)](https://github.com/tristan-weil/ansible-role-upgrade/actions)

## Role Variables

Available variables are listed below, (see also `defaults/main.yml`).

Mandatory variables:

| Variable      | Description |
| :------------ | :---------- |

Optional variables:

| Variable      | Default | Description |
| :------------ | :------ | :---------- |
| upgrade_completed_then_reboot | False | *True / False*: reboot the host after upgrade |

## Example Playbook

    - hosts: 'webservers'
      roles:
        - role: 'ansible-role-upgrade'

## Todo

None.

## Dependencies

None.

## Supported platforms

See [meta/main.yml](https://github.com/tristan-weil/ansible-role-upgrade/blob/master/meta/main.yml)

## License

See [LICENSE.md](LICENSE.md)
