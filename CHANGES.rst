Changelog
=========

Version 0.2.1 [unreleased]
--------------------------

WIP

Version 0.2.0 [2017-05-24]
--------------------------

- `#3 <https://github.com/openwisp/openwisp-controller/issues/3>`_:
  [feature] Added support for template tags
- `#7 <https://github.com/openwisp/openwisp-controller/issues/7>`_:
  [feature] Added ``Device`` model
- `#9 <https://github.com/openwisp/openwisp-controller/issues/9>`_:
  [admin] Load default templates JS logic only when required
- `298b2a2 <https://github.com/openwisp/openwisp-controller/commit/298b2a2>`_:
  [admin] Avoid setting ``extra_content`` to mutable object
- `d173c24 <https://github.com/openwisp/openwisp-controller/commit/d173c24>`_:
  [migrations] Squashed ``0001`` and ``0002`` to avoid postgres error
- `f5fb628 <https://github.com/openwisp/openwisp-controller/commit/f5fb628>`_:
  [migrations] Updated indexes
- `6200b7a <https://github.com/openwisp/openwisp-controller/commit/6200b7a>`_:
  [Template] Fixed ``auto_client`` bug

Version 0.1.4 [2017-04-21]
--------------------------

- `#2 <https://github.com/openwisp/openwisp-controller/issues/2>`_:
  [admin] Added templates in config filter

Version 0.1.3 [2017-03-11]
--------------------------

- `db77ae7 <https://github.com/openwisp/openwisp-controller/commit/db77ae7>`_:
  [controller] Added "error: " prefix in error responses

Version 0.1.2 [2017-03-15]
--------------------------

- `3c61053 <https://github.com/openwisp/openwisp-controller/commit/3c61053>`_:
  [admin] Ensure preview button is present
- `0087483 <https://github.com/openwisp/openwisp-controller/commit/0087483>`_:
  [models] Converted ``OrganizationConfigSettings`` to UUID primary key

Version 0.1.1 [2017-03-10]
--------------------------

- `cbca4e1 <https://github.com/openwisp/openwisp-controller/commit/cbca4e1>`_:
  [users] Fixed integration with `openwisp-users <https://github.com/openwisp/openwisp-users>`_

Version 0.1.0 [2017-03-08]
--------------------------

- added multi-tenancy (separation of organizations) to `openwisp2 <http://openwisp.org>`_
- added email confirmation of new users (via `django-allauth <http://www.intenct.nl/projects/django-allauth/>`_)
