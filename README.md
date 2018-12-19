ansible-kea
===========

This role install Kea DHCP Server and perform initial configuration.

Requirements
------------

Kea DHCP Server support four differents database backends to store the lease
information. This role only install clients for those backends and not databse
backends themselves.
Depending of your choose you will need a running database backends for
MySQL / PostreSQL / Cassandra

Role Variables
--------------

A description of the settable variables for this role should go here, including
any variables that are in defaults/main.yml, vars/main.yml, and any variables
that can/should be set via parameters to the role. Any variables that are read
from other roles and/or the global scope (ie. hostvars, group vars, etc.) should
be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in
regards to parameters that may need to be set for other roles, or variables that
are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-kea, x: 42 }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a
website (HTML is not allowed).
