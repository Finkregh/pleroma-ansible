# pleroma-ansible
Easily install and configure a pleroma instance.
=========

Install pleroma, and if required, can also makes it avalaible over Tor.

Requirements
------------

U don't need anything specific. Just Debian 8 or 9. 

Role Variables
--------------

tor_enabled: yes or no, but by default no.
only_tor: yes or no, but by default no
domain: your fqdn, but by default your current fqdn

Dependencies
------------



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
            tor_enabled: no
            domain: pandjeed.example

License
-------

GPLv3.0
