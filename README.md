# Ansible Role: justniffer


Build status for this role: [![Build Status](https://travis-ci.org/PeterMosmans/ansible-role-justniffer.svg)](https://travis-ci.org/PeterMosmans/ansible-role-justniffer)


This role installs justniffer straight from the github source. The following tool is built:
* [justniffer](https://github.com/onotelli/justniffer)

After running, justniffer will be installed for all users.


## Requirements


None.

## Role Variables


None.

## Dependencies


None.

## Example Playbook


```
- hosts: all
  become: yes
  become_method: sudo
  roles:
    - role: PeterMosmans.justniffer
```
This example will configure, build and install justniffer

## License

GPLv3

## Author Information


Created by Peter Mosmans for [Go Forward](https://www.go-forward.net). Feedback always appreciated.
