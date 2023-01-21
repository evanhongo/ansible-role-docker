# Ansible role for installing or updating docker-engine using the repository

[![Project is](https://img.shields.io/badge/Project%20is-fantastic-ff69b4.svg)](https://github.com/evanhongo/ansible-role-docker)

## Role Variables

- ## (optional) **docker_engine_version**
  ## specifies docker-engine version.

<br />

## Playbook Example

### Install role globally:

```sh
ansible-galaxy install evanhongo.docker
```

### Install role locally:

```sh
ansible-galaxy install --roles-path roles evanhongo.docker
```

### Playbook:

```yaml
- hosts: servers
  roles:
    - role: evanhongo.docker      
      docker_engine_version: 20.10.22
```