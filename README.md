Nodejs
=========

[![Build Status](https://travis-ci.org/charliemaiors/nodejs.svg?branch=master)](https://travis-ci.org/charliemaiors/nodejs)

This role will install nodejs environment and npm on CentOS, Ubuntu or Archlinux.

Requirements
------------

This role has no requirements.

Role Variables
--------------

The role has only one variable ```lts```, which is boolean and enable the installation of lts version instead of the latest.

Example Playbook
----------------

This role allows the user to choose between the newest version and the lts one.

    - hosts: servers
      roles:
         - { role: nodejs, lts: true }

License
-------

GNU GPL

Author Information
------------------

This role was created in 2018 by Carlo Maiorano as developer for Dipartimento di Informatica - Scienza e Ingegneria of Alma Mater Studiorum directed and supervisioned by Paolo Bellavista as Group Leader.
