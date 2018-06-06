[![Ansible Galaxy](https://img.shields.io/badge/role-likg.apt--repo--sury--org-blue.svg?style=flat)](https://galaxy.ansible.com/likg/apt-repo-sury-org/)
[![Build Status](https://travis-ci.org/likg/ansible-role-apt-repo-sury-org.svg?branch=master)](https://travis-ci.org/likg/ansible-role-apt-repo-sury-org)

# Ansible Role: APT packages.sury.org/php repo role
=========

Install APT packages.sury.org/php repo on Debian/Ubuntu.

Requirements
------------

No special requirements.

Role Variables
--------------

Available variables/default values can be found in [defaults/main.yml](defaults/main.yml).

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: yes
      roles:
         - { role: likg.apt-repo-sury-org }

License
-------

MIT

Author Information
------------------

This role was created by Lik.
