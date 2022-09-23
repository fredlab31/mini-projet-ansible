php
=========

Install Apache and PHP 7.4 on CentOS 

Role Variables
--------------

remi_repo: URL of the remi repository rpm for yum to use.

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: php
          vars:
            remi_repo: URL

License
-------

BSD

Author Information
------------------

Hi from Fred !
