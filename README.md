# Ansible Role: portainer

[![Lint](https://github.com/dcjulian29/ansible-role-portainer/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-portainer/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-portainer.svg)](https://github.com/dcjulian29/ansible-role-portainer/issues)

This an Ansible role to install portainer and docker. Portainer is an excellent UI for docker and quickly spinning up containers using compose.

## Requirements

- Internet Connection to download container images.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.portainer
  src: https://github.com/dcjulian29/ansible-role-portainer.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- Ansible Role: `dcjulian29.docker`
- Ansible Role: `geerlingguy.pip`
