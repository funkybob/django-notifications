Changelog
=========

0.8.0
-----

0.8 is the last major version supports Django 1.4~1.6, version 0.8.0 will go into bugfix mode, no new features will be accepted.

- Bugfixes for live-updater, and added a live tester page (@LegoStormtroopr)
- Class-based classes (@alazaro)
- Fixed urls in tests (@alazaro)
- Added app_label to Notification model in order to fix a Django 1.9 deprecation warning (@Heldroe)
- django-model-utils compatible issue (must >=2.0.3 and <2.4) (@zhangz)
- Reliable setup.py versioning (@yangyubo)

0.7.1
-----

- Able to pass level when adding notification (@Arthur)
- Fix deprecation notice in Django 1.8 (@ashokfernandez)
- Fix Python 3 support for notification model (@philroche)
- Bugfix for wrong user unread notification count (@Geeknux)
- A simple javascript API for live-updating specific fields within a django template (@LegoStormtroopr)
- Add missing migration for Notification model (@shezadkhan137)

0.7.0
-----

- Add filters and displays to Django model Admin
- Support Django 1.8, compatible with both django-south (django < 1.7) and built-in schema migration (django >= 1.7)
- Compatible with Python 3
- Test fixtures, and integrated with travis-ci

0.6.2
-----

- Fix README.rst reStructuredText syntax format
- Use relative imports
- Add contributors to AUTHORS.txt

0.6.1
-----

- Add support for custom user model
- mark_as_unread
- Require django-model-utils >= 2.0.3
- Use different `now` function according to the `USE_TZ` setting

0.6.0
-----

- Improve documentation
- Add unicode support at admin panel or shell

0.5.5
-----

Support for arbitrary data attribute.

0.5.1
-----

Fix package descriptions and doc links.

0.5
---

First version based on `django-activity-stream <https://github.com/justquick/django-activity-stream>`_ v0.4.3

