wordpress
=========

Install WordPress on CentOS

Requirements
------------

A functionnal LAMP stack.

Role Variables
--------------

wordpress_source: URL of the source tar file containing WordPress files
user: the Ansible user that will be used for deployment
web_folder: Location of the web folder for Apache
mysql_db_user: Name of the mysql admin user that will manage the DB
mysql_db_user_password: Password for the mysql admin user
mysql_db_name: Name of the database to used by WordPress

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: mysql
          vars:
            wordpress_source: URL
            user: ansible_user
            web_folder: /path/to/html
            mysql_db_user: admin_user
            mysql_db_user_password: admin_pass
            mysql_db_name: my_db

License
-------

BSD

Author Information
------------------

Bien le bonjour de Fred !
