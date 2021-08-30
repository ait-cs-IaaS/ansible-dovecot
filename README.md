# Ansible Role: dovecot

This role installs and manages [Dovecot](https://www.dovecot.org/).

## Requirements

- Ansible 2.1+
- Debian-based linux-distribution

## Dependencies

None.

## Role Variables


## Configuration example

```yaml
- name: Configure mailserver
  hosts: mailserver
  roles:
    - dovecot
```

## Licence

GPL-3.0
