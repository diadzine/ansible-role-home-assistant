Ansible role Home Assistant
===========================

Ansible role to deploy Home Assistant using pip3.

Requirements
------------

None

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

  homeassistant_config_dir: /srv/home-assistant-config

The default config dir.

  homeassistant_user: homeassistant

The default Home Assistant user.

  homeassistant_port: 8123

The default port used by Home Assistant.

  homeassistant_version: latest

The specific version of Home Assistant to install or 'latest' to install latest
version of Home Assistant.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: home-assistant }

License
-------

BSD

Author Information
------------------

This role was created in 2018 by [Aymeric Bringard](https://github.com/diadzine).
