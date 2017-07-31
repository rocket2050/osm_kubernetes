Role Name
=========


Configures an etcd cluster for centos(7)

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below.

master_hostname: "master"
minion_hostname: "minion"

You can give the hostname or server_ip of the servers.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: osm_kubernetes }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
