# Ansible Role: Ovirt Guest Agent
[![Build Status](https://travis-ci.org/sbaerlocher/ansible.ovirt-guest-agent.svg?branch=master)](https://travis-ci.org/sbaerlocher/ansible.ovirt-guest-agent)

## Description

Ansible role for installing Ovirt Guest Agent on installs RHEL/CentOS.

## Installation

```
$ ansible-galaxy install sbaerlocher.ovirt-guest-agent
```

## Requirements

This role requires Ansible 2 or higher, and platform requirements are listed
in the metadata file.

## Dependencies

None

## Example Playbook

```yml
    - hosts: all
      roles:
        - sbaerlocher.ovirt-guest-agent
```

## Changelog

### 1.2

* add new role ckeck
* remove eple repo

### 1.1

* add debian support
* add new syntax
* add tags
* fix bugs

### 1.0

* initial release


## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

MIT