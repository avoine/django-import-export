Changelog for django-import-export
==================================

0.2.1 (unreleased)
------------------

- Nothing changed yet.


0.2.0 (2014-01-30)
------------------

- Python 3 support


0.1.6 (2014-01-21)
------------------

* Additional hooks for customizing the workflow (#61)

0.1.5 (2013-11-29)
------------------

* Prevent queryset caching when exporting (#44)

* Allow unchanged rows to be skipped when importing (#30)

* Update tests for Django 1.6 (#57)

* Allow different ``ResourceClass`` to be used in ``ImportExportModelAdmin``
  (#49)

0.1.4
-----

* Use `field_name` instead of `column_name` for field dehydration, FIX #36

* Handle OneToOneField,  FIX #17 - Exception when attempting access something
  on the related_name.

* FIX #23 - export filter not working

0.1.3
-----

* Fix packaging

* DB transactions support for importing data

0.1.2
-----

* support for deleting objects during import

* bug fixes

* Allowing a field to be 'dehydrated' with a custom method

* added documentation

0.1.1
-----

* added ExportForm to admin integration for choosing export file format

* refactor admin integration to allow better handling of specific formats
  supported features and better handling of reading text files

* include all avialable formats in Admin integration

* bugfixes

0.1.0
-----

* Refactor api
