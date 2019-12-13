# Write /etc/hosts

Ansible role that defines the /etc/hosts file.

## Requirements

None

## Role Variables

Available variables with default values in `defaults/main.yml`.

## Dependencies

None

## Example Playbook

- name: Define /etc/hosts
  hosts: all
  become: yes
  roles:
    - role: gcoop-libre.etc_hosts

## License

GNU General Public License, GPLv3.

## Author Information

This role was created in 2019 by Martin Ales, worker cooperative of [gcoop Cooperativa de Software Libre](http://www.gcoop.coop/).
