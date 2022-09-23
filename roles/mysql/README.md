mysql
=========

Install Mysql on CentOS

Role Variables
--------------

mysql_root_password: Password for the root user of mysql
mysql_db_user: Name of the new admin account created during install
mysql_db_user_password: Password for the new account
mysql_db_name: Database name

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: mysql
          vars:
            mysql_root_password: 123
            mysql_db_user: admin_user
            mysql_db_user_password: admin_pass
            mysql_db_name: my_db

License
-------

BSD

Author Information
------------------

Fred says hello.
