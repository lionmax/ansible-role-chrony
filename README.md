marklee77.chrony
================

[![Build Status](https://travis-ci.org/marklee77/ansible-role-chrony.svg?branch=master)](https://travis-ci.org/marklee77/ansible-role-chrony)

Role to install chrony ntp server for ubuntu in client mode.

Role Variables
--------------

- chrony_ntp_servers: list of ntp servers, defaults to a set from pool.ntp.org.

Example Playbook
-------------------------

    - hosts: all
      roles:
        - marklee77.chrony

License
-------

GPLv2

Author Information
------------------

http://stillwell.me
