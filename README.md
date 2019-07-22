Role Name
=========

This role will install PHP for web servers on RPM based distributions (RHEL, CentOS, etc) using yum.

Dependencies
--------------
Requires reallryansmith.apache-yum ansible role

Example Playbook
----------------

---
- hosts: all
  become: yes
  roles:
    - php-webserver

License
-------

BSD

Author Information
------------------

Ryan Smith!
