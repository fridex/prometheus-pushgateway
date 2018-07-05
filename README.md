Role Name
=========

This role will deploy a Prometheus Pushgateway to an OpenShift project.

Requirements
------------

An all set OpenShift project.

Role Variables
--------------

Only the OpenShift project name.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: thoth-station.prometheus-pushgateway, project: test }

License
-------

GPLv3+