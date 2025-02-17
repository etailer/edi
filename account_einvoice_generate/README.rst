==========================
Account e-invoice Generate
==========================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fedi-lightgray.png?logo=github
    :target: https://github.com/OCA/edi/tree/16.0/account_einvoice_generate
    :alt: OCA/edi
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/edi-16-0/edi-16-0-account_einvoice_generate
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/226/16.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5| 

This is a technical module that ensure compatibility between the e-invoice generation modules of the `OCA/edi project <https://github.com/OCA/edi/>`_. It doesn't bring any feature by itself. You must also install one of the 2 OCA modules that generate electronic invoices:

* **account_invoice_ubl**: add support for the UBL format (Universal Business Language),
* **account_invoice_facturx**: add support for the `Factur-X <http://fnfe-mpe.org/factur-x/factur-x_en/>`_ format.

See the README of each module for more information.

These 2 modules are able to embed an XML file in the PDF invoice and
this module ensure that these 2 modules are compatible.

**Table of contents**

.. contents::
   :local:

Installation
============

Before installing the module, you must **uninstall** the module **account_edi** from the official addons. As the account_edi module is auto-installable, it is certainly already installed on your Odoo database.

For that, go to the *Apps* menu, remove the *Apps* filter, search for the module *account_edi* (the title of the module is *Import/Export Invoices From XML/PDF*). Then click on the button *Module info* and then on the button *Uninstall*.

Configuration
=============

The new configuration parameter *XML Format embedded in PDF invoice*
is available in the menu *Invoicing > Configuration > Settings*.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/edi/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/OCA/edi/issues/new?body=module:%20account_einvoice_generate%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Akretion
* Onestein

Contributors
~~~~~~~~~~~~

* Alexis de Lattre <alexis.delattre@akretion.com>
* Andrea Stirpe <a.stirpe@onestein.nl>
* Shine IT <contact@openerp.cn>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-alexis-via| image:: https://github.com/alexis-via.png?size=40px
    :target: https://github.com/alexis-via
    :alt: alexis-via

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-alexis-via| 

This module is part of the `OCA/edi <https://github.com/OCA/edi/tree/16.0/account_einvoice_generate>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
