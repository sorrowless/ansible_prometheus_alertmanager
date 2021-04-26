# sbog/prometheus_alertmanager

[![Build Status](https://travis-ci.com/sorrowless/ansible_prometheus_alertmanager.svg?branch=master)](https://travis-ci.com/sorrowless/ansible_prometheus_alertmanager)
[![Ansible Role](https://img.shields.io/ansible/role/54493)](https://galaxy.ansible.com/sorrowless/prometheus_alertmanager)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/54493)](https://galaxy.ansible.com/sorrowless/prometheus_alertmanager)
[![Ansible Role](https://img.shields.io/ansible/role/d/54493)](https://galaxy.ansible.com/sorrowless/prometheus_alertmanager)
[![GitHub](https://img.shields.io/github/license/sorrowless/ansible_prometheus_alertmanager)](https://github.com/sorrowless/ansible_prometheus_alertmanager/blob/master/LICENSE)

An Ansible role which installs and configures [Prometheus Alertmanager](https://prometheus.io/docs/alerting/latest/alertmanager/) on Linux

## Requirements

Ansible 2.8+

## Role Variables

You can see all vars in `defaults/main.yml` vars file.

## Dependencies

None

## Example Playbook

```yaml
- name: Ensure prometheus_alertmanager DB
  hosts: prometheus_alertmanagers
  remote_user: root

  roles:
    - prometheus_alertmanager
```

## License

Apache 2.0

## Author Information

This role was created by [Stan Bogatkin](https://sbog.ru).
