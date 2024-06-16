Role Name
=========

Ansible role to install a Red Hat Developer Hub POC on OpenShift.

This will automate the [RHDH workshop exercise](https://github.com/raffaelespazzoli/rhdh-exercises/blob/main/lab-prep/readme-preparation.md)

Requirements
------------

Python pip dependencies: [requirements.txt](requirements.txt)

Role Variables
--------------

Defaults vars: [main.yml](defaults/main.yml)


Dependencies
------------

Ensure you are loged in to an OpenShift cluster, with a user that has `cluster-admin` privileges. 


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: rhdh_poc }

License
-------

BSD

Author Information
------------------

This role was created in 2024 by [Bart Joris](https://www.bartjoris.be). 
