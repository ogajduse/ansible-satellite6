Ansible Role for Partitioning Disk
==================================

This Ansible role removes home partition and extends root partition.

Requirements
------------

No Requirements are required for this role.

Role Variables
--------------

No variables required for this role.

Dependencies
------------

This role is not dependent upon any galaxy roles.

Example Playbook
----------------

Here is a simple example of partitioning-disk role:

- hosts: localhost
  remote_user: root
  roles:
    - partition-disk

License
-------

 GNU GENERAL PUBLIC LICENSE

    Version 3, 29 June 2007

 Copyright (C) 2007 Free Software Foundation, Inc.


Author Information
------------------

This is developed by Satellite QE team, irc: #robottelo on Freenode
