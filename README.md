Role Name
=========

Installs Apache Ignite Hadoop accelerator

Role Variables
--------------

Role expects IGNITE_HOME to point to where ignite installed

Dependencies
------------

Depends on dropoutlabs.ignite to have ignite

Example Playbook
----------------

How to use role:

    - hosts: ignites
      roles:
         - dropoutlabs.ignite-hadoops

License
-------

BSD

