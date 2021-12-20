Role Name
=========

A simple Ansible Role to sets the Gnome Shell "switch-windows" shortcut to use Alt+Tab

Example Playbook
----------------

Playbook "user-config.yml"

    - hosts: localhost
      roles:
      - dotmjs.gnome_shell_alt_tab_windows

Invocation

    ansible-playbook -i localhost --ask-become-pass user-config.yml

License
-------

Apache 2.0

Author Information
------------------
MJS
