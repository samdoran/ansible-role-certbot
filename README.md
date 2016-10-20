Certbot
=========
[![Galaxy](https://img.shields.io/badge/galaxy-samdoran.certbot-blue.svg?style=flat)](https://galaxy.ansible.com/samdoran/certbot)
[![Build Status](https://travis-ci.org/samdoran/ansible-role-certbot.svg?branch=master)](https://travis-ci.org/samdoran/ansible-role-certbot)

[Certbot](https://certbot.eff.org/about/) automatically configures TLS certificates for various web servers for free.

Requirements
------------

- samdoran.repo-epel

Role Variables
--------------

| Name              | Default Value       | Description          |
|-------------------|---------------------|----------------------|
| `` | `` |  |


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: all
      roles:
         - samdoran.certbot

License
-------

MIT
