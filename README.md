[![Build Status](https://travis-ci.org/teampants/ansible-haproxy.svg?branch=develop)](https://travis-ci.org/teampants/ansible-haproxy)
# ansible-haproxy
Installs haproxy 1.6-stable

## Example Playbook

    - hosts: load_balancers
      roles:
        - role: teampants.haproxy
