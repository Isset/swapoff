isset.swapoff [![pipeline status](https://gitlab.isset.nl/operations/isset.docker/badges/master/pipeline.svg)](https://gitlab.isset.nl/operations/isset.docker/commits/master)
=========

_Removes swap from server_

Requirements
------------

Ansible 2.5 or above is highly recommended.

Role Variables
--------------

    n/a


Dependencies
------------

    n/a

Example Playbook
----------------

    - hosts: all
      become: yes
      roles:
        - isset.swapoff

License
-------

MIT

Author Information
------------------

Gerben Geijteman <gerben@isset.nl>
