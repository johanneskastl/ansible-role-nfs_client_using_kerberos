nfs_client_using_kerberos
=========

Preparing a client to mount a kerberized NFSv4 share.

Requirements
------------

You should have a kerberized NFSv4 server. And your client should be already prepared to get a valid Kerberos ticket (see [this role](https://github.com/johanneskastl/ansible-role-configure_kerberos_clients)).

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: 'johanneskastl.nfs_client_using_kerberos'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
