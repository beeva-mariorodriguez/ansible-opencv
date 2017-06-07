opencv
======

[OpenCV](http://opencv.org/) installation role for ansible (from source)

Requirements
------------

none

Role Variables
--------------

* ``version``: default: "3.2.0"
* ``install_prefix``: default: "/usr/local"
* ``reinstall``: overwrite current installation (default: False)
* ``delete_sources``: delete sources after installation (default: False)

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: opencv, version: "3.1.0" }

Versions Tested
---------------

* 3.1.0 does not compile with CUDA
* 3.2.0 OK

License
-------

BSD

Author Information
------------------

Mario Rodríguez

