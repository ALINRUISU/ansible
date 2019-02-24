Role Name
=========

Commons role for CentOS 7 which provides a combination of networking tools, security, utility and services

Services
- NTPD
- AuditD
- AUTOFS

Monitoring
- NodeExporter

Security
- MOTD
- AuditD / AIDE
- SSHD
- SElinux (permissive)
- Auditing info

Networking
- Disable IPV6
- Remove FirewallD
- Install IPTABLES
 
Utilities
- git
- mtr
- nload
- nettools


Requirements
------------
No additional requirements, this is a generic Centos 7 Commons Role

Role Variables
--------------



Dependencies
------------

No dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
