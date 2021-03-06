# Ansible Role: barman

Run barman backups and install/setup barman on Debian and Ubuntu servers.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

## Dependencies

- AlphaNnodes.postgresql-client

## Installation

### Ansible 2+

Using ansible galaxy cli:

```shell
ansible-galaxy install alphanodes.barman
```

## Example Playbook

```yaml
    - hosts: your-barman-server
      vars:
        barman_task: setup
        barman_postgresql_password: yoursecretpassword
      roles:
        - alphanodes.barman
```

## License

GPL Version 3

## Author Information

This role was created in 2022 by [AlphaNodes](https://alphanodes.com/).
