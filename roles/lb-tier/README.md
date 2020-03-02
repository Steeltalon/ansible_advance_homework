Role Name
=========

This role is used to deploy the HA Proxy service.  The main task is deploy_haproxy.yml

Requirements
------------

pre-requisite is the haproxy.conf.j2 template

Role Variables
--------------

haproxy_config_file - location of the configuration on the frontend servers
GUID = GUID for three tier deployment.  Presently this should reflect a value of 40b5

Dependencies
------------
This uses the haproxy.conf.j2 configuration file


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
