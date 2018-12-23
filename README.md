# pleroma-ansible
Easily install and configure a pleroma instance.
=========

Install pleroma and makes it avalaible over Tor.

Requirements
------------

U don't need anything specific. Just Debian 8 or 9. 

Variables
---------

pleroma_passwd: 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      user: root
      tasks:
        - name: Install Pleroma with Tor
          include_role:
            name: pandjeed.pleroma
          vars:
            pleroma_passwd: randombullshit

License
-------

GPLv3.0
