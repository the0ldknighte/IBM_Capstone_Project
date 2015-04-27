================
ansible-graphite
================

Simple Ansible playbook and role for setting up Graphite

platforms
=========

Only supports Ubuntu 14.04 LTS (trusty) right now.

usage
=====

Make sure you have ansible installed.

Add the host you wish to configure under
the 'graphite_servers' group of your hosts file::

  [graphite_servers]
  my_new_graphite_server.example.com

Run the ansible playbook::

  $ ansible-playbook graphite.yaml

license
=======

Apache 2.0 Licensed - see LICENSE for details
