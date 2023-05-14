Ansible Role: Workrave
=============================

[![Build Status](https://github.com/webarchitect609/ansible-role-workrave/workflows/build/badge.svg?branch=master)](https://github.com/webarchitect609/ansible-role-workrave/actions?query=workflow%3Abuild)
[![Latest version](https://img.shields.io/github/v/tag/webarchitect609/ansible-role-workrave?sort=semver)](https://github.com/webarchitect609/ansible-role-workrave/releases)
[![Downloads](https://img.shields.io/ansible/role/d/56021)](https://galaxy.ansible.com/webarchitect609/workrave)
[![License](https://img.shields.io/github/license/webarchitect609/ansible-role-workrave)](LICENSE.md)
[![More stuff from me](https://img.shields.io/badge/galaxy-webarchitect609-000)](https://galaxy.ansible.com/webarchitect609)

Installs [Workrave](https://workrave.org) from the official deb repository.

Requirements
------------

None.

Role Variables
--------------

None of the variables need to be altered for installing the latest stable version of the application.
However, all available variables are listed below, along with default values (see `defaults/main.yml`):

    workrave_package: workrave-gnome

Package name to install

    workrave_deb_source: "deb http://repo.yandex.ru/yandex-disk/deb/ stable main"

Repository url.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: webarchitect609.workrave }

License & Author Information
-------
[BSD-3-Clause](LICENSE.md)
