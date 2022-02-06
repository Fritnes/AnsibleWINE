Role "WINE"
=========

https://linuxconfig.org/install-lutris-on-ubuntu-20-04-focal-fossa-linux

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: AnsibleWINE, when: ansible_system == 'Linux' }

Author Information
------------------

fritnes
https://github.com/Fritnes

