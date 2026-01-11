# Vector Role

Ansible role for installing and configuring Vector log collector.

## Requirements

- Ansible 2.9+
- Ubuntu/Debian or CentOS/RHEL

## Role Variables

See `defaults/main.yml` for all available variables.

### Main variables:
- `vector_version`: Vector version to install (default: "0.36.0")
- `vector_config_dir`: Configuration directory (default: "/etc/vector")
- `vector_data_dir`: Data directory (default: "/var/lib/vector")

## Example Playbook

```yaml
- hosts: servers
  become: yes
  roles:
    - role: vector
      vector_version: "0.36.0"
