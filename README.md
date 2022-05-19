vector-role
=========

Install vector 

Requirements
------------

-

Role Variables
--------------

VARs in default:
VECTOR_VER: "0.21.2"
VECTOR_DOWNLOAD_DIR: "/vectordistrib"
VECTOR_DIR: "/vector"
VECTOR_DATA: "/var/lib/vector"



Dependencies
------------

-

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: vector-role }

License
-------

BSD

Author Information
------------------

Danil054 for Netology
