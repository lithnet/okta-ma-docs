.. Okta Management Agent documentation master file, created by
   sphinx-quickstart on Thu Feb 17 14:29:14 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Okta Management Agent for FIM 2010 R2 and MIM 2016
######################################################################

The Lithnet Okta Management Agent provides support for managing Okta users with FIM 2010 R2 and higher. 

It provides the ability to create, update, and delete okta-managed users, as well as manage certain attributes on AD-managed users. 

########
Features
########
------------


* Supports the import and export of Okta-managed users
* Supports the import of groups
* Supports the syncing of passwords to Okta

###################
System Requirements
###################
------------



The Lithnet Okta MA requires FIM 2010 R2 at least version 4.1.3441, and .NET Framework 4.6.


Getting started
===============

1. Download and install the management agent from the `releases page <https://github.com/lithnet/okta-managementagent/releases>`_
2. Create a service account in Okta and `obtain an API token <https://developer.okta.com/docs/api/getting_started/getting_a_token>`_
3. :doc:`Create the management agent </Create-the-management-agent>`



.. toctree::
   :hidden:
   :maxdepth: 2
   :caption: Lithnet OKTA Management Agent

   Home <self>
   Create-the-management-agent

