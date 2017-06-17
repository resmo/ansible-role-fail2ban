# Ansible Fail2Ban Role
An ansible role for installing fail2ban.

This is based/forked from resmo.fail2ban

## Usage:

    ---
    - hosts: all
      remote_user: root
      roles:
      - sigio.fail2ban

## Specify your ignoreip's

    fail2ban_config_ignoreip: 1.2.3.4  5.6.7.8  10.20.30/24

## Homepage: 

https://github.com/sigio/ansible-role-fail2ban
