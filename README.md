[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Build Status](https://travis-ci.org/teampants/ansible-haproxy.svg?branch=master)](https://travis-ci.org/teampants/ansible-haproxy)
# ansible-haproxy
Installs haproxy 1.6-stable

## Example Playbook

    - hosts: load_balancers
      roles:
        - role: teampants.haproxy
