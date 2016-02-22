Ansible wordpress php7 ready to fly
===

[![Circle CI](https://circleci.com/gh/FinalCoffee/ansible-wordpress-ready-to-fly.svg?style=shield)](https://circleci.com/gh/FinalCoffee/ansible-wordpress-ready-to-fly) [![Build Status](https://travis-ci.org/FinalCoffee/ansible-wordpress-ready-to-fly.svg?branch=master)](https://travis-ci.org/FinalCoffee/ansible-wordpress-ready-to-fly)

## Summary

This is for lazy man to use wordpress.

## Role Variables

### Mandatory variables

None.

### Optional variables

User-installable configuration files (by Ansible's template system):

## Handlers

- `restart nginx`

- `restart restart php-fpm`

## Usage


### Step 1: add role

Add role name `finalcoffee.ansible-wordpress-ready-to-fly` to your playbook file.


### Directory layout

This is a ready to fly version of ansible script for wordpress php7.

## Dependencies

None.


## License

MIT License. See the [LICENSE file](LICENSE) for details.


## History

Rewritten from my pre-Galaxy version: [server-config-template](https://github.com/William-Yeh/server-config-template).
