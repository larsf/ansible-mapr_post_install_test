mapr_post_install_test
=========

A few smoke tests to make sure the cluster works.

Requirements
------------

You should have a cluster that is up and running.

Role Variables
--------------

Dependencies
------------


Example Playbook
----------------

    - hosts: cluster
      roles:
         - { role: mapr_post_install_test }

License
-------

MIT

Author Information
------------------

Vince Gonzalez
