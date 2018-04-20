.. smartva-dhis2 documentation master file, created by
   sphinx-quickstart on Fri Apr 20 12:15:30 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

smartva-dhis2
==============

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   Installation Guide <installation>
   Configuration <configuration>
   Local Database <local_database>
   Components <components>


A Python package for the integration of Verbal Autopsy Data into DHIS2.

It downloads `ODK <https://opendatakit.org>`_ Briefcases,
runs the SmartVA / Tariff 2.0 algorithm to find the most probable Cause of Death,
transforms it to a DHIS2-compatible Program Event and posts it to DHIS2.
Any data validation errors or DHIS2 import errors are written to a local SQLite database which can be queried via
the command line.

The code is hosted on Github: https://github.com/D4H-VA/smartva-dhis2

Links
------

- `crvsgateway.info <https://crvsgateway.info/learningcentre/cause-of-death-in-crvs>`_
- `dhis2.org <https://www.dhis2.org>`_