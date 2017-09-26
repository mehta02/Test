Role Name
=========
This is a role for creating LVM in Ubuntu Redhat & CentOS


Requirements
------------

None


Role Variables
--------------

Defined in defaults and vars

Dependencies
------------

None



Example Playbook
----------------

playbook

---
-hosts: [webserver]
 become: true
 gather_facts: False
 roles:
   - lvm



License
-------

BSD

Author Information
------------------

Shubham Mehta
