Role Name
=========


Requirements
------------


Role Variables
--------------
http/https - 80/443/tcp
LDAP/LDAPS - 389/636/tcp
Kerberos - 88/464/tcp/udp
DNS - 53/tcp/udp
NTP - 123/udp
Dogtag Certificate System LDAP 7389/tcp

if only adding a VM then install `ipa-client`
if adding a VM and using for administrative then install `ipa-client ` and `ipa-admintools`




Dependencies
------------

firewalld

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
