Role Name
=========

This role deploys two Docker containers, one for Nexus3 and one for NGiNX. NGiNX acts as an SSL proxy for the Nexus repo.

Requirements
------------

This role requires either RHEL or CentOS version 7.x

Role Variables
--------------

TO-DO

Dependencies
------------

None.

Example Playbook
----------------

Included in this package is a test playbook in tests/test.yml
<pre>
   ---
   - hosts: localhost
     remote_user: root
     roles:
       - nexus-proxy
</pre>
License
-------

GPLv3

Author Information
------------------

Tim Robinson tim.robinson@atos.net
