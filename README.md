Role Name
=========

Install AWSs SSM Agent on host.

Requirements
------------

At present, only supports RHEL (RPM) based Linux OSes.

Dependencies
------------

This role has no dependencies.

Example Playbook
----------------

To use the role, just include it.

    - hosts: servers
      roles:
         - { role: nimbis.ssm-agent-setup }

License
-------

BSD

Author Information
------------------

Nimbis Services, Inc.  devops@nimbisservices.com
