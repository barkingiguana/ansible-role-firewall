Firewall
=========

Firewall configuration.

Read and understand this before making any changes to your configuration:
  https://www.frozentux.net/iptables-tutorial

Requirements
------------

None

Role Variables
--------------

* `firewall_reload_ipv4`: reload the active firewall for IPv4 when the rules change.
* `firewall_reload_ipv6`: reload the active firewall for IPv6 when the rules change.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: barkingiguana.firewall
           firewall_reload_ipv4: no

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
