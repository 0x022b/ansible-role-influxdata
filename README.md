# Ansible Role: InfluxData

![Ansible Galaxy](https://github.com/0x022b/ansible-role-influxdata/workflows/Ansible%20Galaxy/badge.svg)

Ansible role that configures InfluxData repository.

## Requirements

None.

## Role Variables

Available variables are listed below with default values.

```yaml
influxdata_repository_state: present
```

Variable to control the state of InfluxData repository.

## Dependencies

None.

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: 0x022b.influxdata
```

## Versioning

This project uses [Semantic Versioning][semver].

## License

MIT

[semver]: https://semver.org/
