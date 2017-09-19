Role Name
=========

This is a role for installing apache2 on ubuntu and centos machine

Requirements
------------

Basic package requirement is python package

Role Variables
--------------

No variable are defined 

Dependencies
------------

Only dependency for running on the servers is  Python package without which our ansible roles will not work

Example Playbook
----------------

An insight of how the playbook looks like

    - hosts: webserver
      roles:
         - {apache2}

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
