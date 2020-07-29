Role Name
=========

Hopla.cloud role for ansible to install a simple Drupal.

Requirements
------------

Ubuntu 18.04

Role Variables
--------------

user_email: "exemple@domain.com"

Dependencies
------------

- hoplacloud.linux_update
- hoplacloud.linux_motd
- hoplacloud.linuxbase
- hoplacloud.apache_php
- hoplacloud.fail2ban
- hoplacloud.proftpd
- hoplacloud.postfix
- geerlingguy.mysql


Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - hoplacloud.drupal

License
-------

GPLv3

Author Information
------------------

Joffrey Skandera for [hopla.cloud](https://hopla.cloud)
