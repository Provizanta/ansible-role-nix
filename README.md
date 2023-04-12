Ansible role: nix
=========

![main Build status](https://github.com/Provizanta/ansible-role-nix/actions/workflows/main.yml/badge.svg)

Install single user install of the nix package manager.

Requirements
------------

None

Role Variables
--------------

These variables are defined in [defaults/main.yml](./defaults/main.yml):

    nix_remove_etc_shell_modifications: true

    nix_add_source_to_user_shells: true

    nix_install_script_url: https://nixos.org/nix/install


Dependencies
------------

None

Example Playbook
----------------

    - hosts: localhost
      roles:
        - role: nix
          vars: {}

License
-------

MIT

Author Information
------------------

Tibor Csóka
