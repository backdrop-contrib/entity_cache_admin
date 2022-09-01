Entity Cache Administration
======================

Entity Cache Administration provides an interface that lets the site
administrator select which entities should be cached at the individual bundle
level. For example, you can choose to cache some content (node) types but not
others.

Installation
------------

- Install this module using [the official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

- Visit the configuration page under Administration > Configuration >
  Development > Performance (admin/config/development/performance) and expand
  the section "Entity Caching." All listed entities are persistently cached by
  default; uncheck any entity/bundle combinations to disable persistent caching
  for that entity/bundle.
  
Bundle-level entity caching was introduced in Backdrop 1.23.0. This module requires at least this version of Backdrop.

Issues
------

Bugs and feature requests should be reported in [the issue queue](https://github.com/backdrop-contrib/entity_cache_admin/issues).

Current Maintainers
-------------------

- [Robert J. Lang](https://github.com/bugfolder)

Credits
-------

- Created for Backdrop CMS by [Robert J. Lang](https://github.com/bugfolder).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.

