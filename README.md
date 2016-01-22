# Ansible Role: Scrapy

[![Build Status](https://travis-ci.org/nerdstein/ansible-role-scrapy.svg?branch=master)](https://travis-ci.org/nerdstein/ansible-role-scrapy)

Installs Scrapy, a web crawler tool, on any Linux or UNIX system.

## Requirements

`pip` should be installed and working.

## Role Variables

None

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
        - nerdstein.scrapy

After the playbook runs, `scrapy` will be accessible via normal system accounts.

## License

MIT / BSD

## Author Information

This role was created in 2016 by [Adam Bergstein](http://nerdstein.net/).
