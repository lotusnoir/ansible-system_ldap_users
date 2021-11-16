# ansible-system_ldap_users

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_ldap_users-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_ldap_users)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_ldap_users.svg)](https://github.com/lotusnoir/ansible-system_ldap_users/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_ldap_users?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56111)](https://galaxy.ansible.com/lotusnoir/system_ldap_users)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56111)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)


Configure access using ansible.

## Requirements

none

## Role variables

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|

## Examples

        ---
        - hosts: system_ldap_users
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-system_ldap_users
          environment:
            http_proxy: "{{ http_proxy }}"
            https_proxy: "{{ https_proxy }}"
            no_proxy: "{{ no_proxy }}

## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

