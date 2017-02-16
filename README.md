python-pip
==========

This role installs [python-pip](https://pip.pypa.io/en/stable/) on an Ubuntu Server following [Official Documentation](https://pip.pypa.io/en/stable/installing/).

Example Playbook
----------------

    - hosts: servers
      roles:
        - { 
          role: 'python-pip'
        }

License
-------

MIT

[![Build Status](https://travis-ci.org/dpujadas/ansible-role-python-pip.svg?branch=master)](https://travis-ci.org/dpujadas/ansible-role-python-pip)