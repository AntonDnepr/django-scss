Changes
*******

0.6.1
------

- Use hashlib instead of django.utils.hashcompat which is deprecated in Django 1.5

0.6
----

- Add staticfiles finder to serve compiled files in dev mode


0.5
----

- Add SCSS_ROOT setting


0.4.1
-----

- Fix unicodedecodeerror with non ascii in scss file

0.4
----
 - Switch to staticfiles.finders when looking up the files in DEBUG mode.
 - Fix the CWD when running scss compiler

0.3
----

- Add support for lookup in STATICFILES_DIRS
- Allow to use Compass

0.2
----

- Log SCSS compilation errors
- Fixed bug with paths on Windows


0.1
----

- Initial release
