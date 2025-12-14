pyluga
========

An easy to use Python wrapper for the Beluga Panel API.

.. toctree::
    :hidden:

    self

Documentation
=============
This documentation is generated from docstrings so the class names do
not usually match the way they are accessed when using BelugaClient.

For example the `get_server()` method documented in the
`pyluga.api.client.servers.base.ServersBase` class is accessed by calling
`client.servers.get_server()`.

The majority of names in BelugaClient match their path minus the class
name, so `pyluga.api.client.account.Account.get_server()` is
`client.account.get_server()`.  Classes named or ending with Base are
imported into the parent namespace.

More example usage can be found can be found in the README at
https://github.com/iamkubi/pyluga.

Client API
==========
The Client API are endpoints available to any Beluga user account and
require a Client API key generated in the account settings.

.. toctree::
    :maxdepth: 1
    :caption: client

    clientapi

Application API
===============
Application API endpoints are only available to Beluga Administrators
and require an Application API key generated in the Admin panel.

.. toctree::
    :maxdepth: 1
    :caption: application

    applicationapi

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
