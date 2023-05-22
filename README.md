# Ansible Role: contojo.awx

**Ansible role for setting up AWX**

## Supported Platforms

| OS Family | Distribution  | Latest | Supported Version(s) | Comment |
|-----------|---------------|--------|----------------------|---------|
| EL        | CentOS        | :x: | Stream9 | |

## Requirements

Ansible Core 2.11 or higher.

## Variables

See [defaults/main.yml](defaults/main.yml) for all variables and their defaults.

## Dependencies

None.

## Example Playbook

```yaml
---

- hosts: all
  become: true
  gather_facts: true
  roles:
    - role: sol1_awx
```
