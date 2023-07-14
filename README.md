[![GitHub issues](https://img.shields.io/github/issues/garutilorenzo/ansible-role-linux-docker)](https://github.com/garutilorenzo/ansible-role-linux-docker/issues)
![GitHub](https://img.shields.io/github/license/garutilorenzo/ansible-role-linux-docker)
[![GitHub forks](https://img.shields.io/github/forks/garutilorenzo/ansible-role-linux-docker)](https://github.com/garutilorenzo/ansible-role-linux-docker/network)
[![GitHub stars](https://img.shields.io/github/stars/garutilorenzo/ansible-role-linux-docker)](https://github.com/garutilorenzo/ansible-role-linux-docker/stargazers)

# Install and configure docker daemon on Linux

Ansible role used to install docker daemon on Linux boxes

## Requirements

Download the role form GitHub:

```
ansible-galaxy install git+https://github.com/garutilorenzo/ansible-role-linux-docker.git
```

## Role Variables

This role accept this variables:

| Var   | Required |  Default | Desc |
| ------- | ------- | ----------- |  ----------- |
| `additional_docker_user`       | `no`       | ``       | Additional docker user to be added on docker group  |
| `http_proxy`       | `no`       | ``       | Porxy used by the docker daemon to reach internet (HTTP)  |
| `https_proxy`       | `no`       | ``       | Porxy used by the docker daemon to reach internet (HTTPS)  |
| `docker_compose_plugin_version`       | `no`       | `2.17.2`       | Only needed for Amazon Linux distributions  |
