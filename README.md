# jtprogru.grafanaoss

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-grafanaoss/CI?label=CI)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-grafanaoss/Release?label=Release)
![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-grafanaoss)
[![Ansible Role](https://img.shields.io/ansible/role/60383)](https://galaxy.ansible.com/jtprogru/grafanaoss/)
[![GitHub tag](https://img.shields.io/github/tag/jtprogru/ansible-role-grafanaoss.svg)](https://github.com/jtprogru/ansible-role-grafanaoss/tags)

Simple role for install [Grafana OSS](https://grafana.com/grafana/download/9.1.6?edition=oss&pg=get&platform=linux&plcmt=selfmanaged-box1-cta1).

## Role Variables

See [`defaults/main.yml`](defaults/main.yml).

## Example Playbook

Example playbook:

```yaml
---
- name: Installing grafanaoss
  hosts: all
  become: true

  roles:
    - jtprogru.grafanaoss
```

## License

See [LICENSE](LICENSE.md)
