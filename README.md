c1.firewall
===========

Ansible role to setup firewall rules using iptables-persistent.

Firewall rules files are created from templates for both IPv4 and IPv6.

Role Variables
--------------

see defaults/main.yml.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: c1.firewall, firewall4_enabled: yes, firewall6_enabled: yes }

License
-------

BSD
