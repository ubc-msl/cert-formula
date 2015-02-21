====
cert
====

Formula to deploy certificates.

.. note::

    See the full `Salt Formulas installation and usage instructions
    <http://docs.saltstack.com/en/latest/topics/development/conventions/formulas.html>`_.

Available states
================

.. contents::
    :local:

``cert``
--------

Deploys given certificates and keys.

Example
=======

Put certificates and keys to */srv/salt/files/cert/* or any other cert directory under file_roots and list them in pillar. See *cert/pillar.example*.

Notes
=====

All certs will be named to *certname.pem* and their key files to *certname.key.pem*.