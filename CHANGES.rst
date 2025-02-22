v1.1.0
======

#8: Added support for camera snapshots.

v1.0.1
======

Refactoring and cleanup.

v1.0.0
======

Removed abodepy compatibility.

v0.8.0
======

#3: Removed test dependency on npm.

#4: Project is now continuously tested on Windows.

Cleaned up usage of unittest in tests.


v0.7.0
======

#1: Passwords are no longer stored in or retrieved from the cache
file. Instead, credentials must be supplied on the command line
or loaded from `keyring <https://pypi.org/project/keyring>`_.
This approach allows the passwords to be stored in a secure,
encrypted, system store. To avoid requiring a username on
each invocation, the default username is loaded from the
ABODE_USERNAME environment variable. If the password is not
present, the user will be prompted for it on the first invocation.

v0.6.0
======

#5: Added support for Abode Cam 2 devices.

#6: Added support for new event codes in ALARM_END_GROUP and
ARM_FAULT_GROUP groups.

v0.5.2
======

Fixed bug in CLI.

v0.5.1
======

Cleaned up README and other references to ``abodepy``.

v0.5.0
======

Added ``abode`` command, superseding ``abodepy``.

v0.4.0
======

Moved modules to ``jaraco.abode``.

v0.3.0
======

Package now uses relative imports throughout.

Prefer pytest for assertions.

General cleanup.

v0.2.0
======

Refreshed packaging. Enabled automated releases.

Require Python 3.7 or later.

v0.1.0
======

Initial release based on `abodepy 1.2.1 <https://pypi.org/project/abodepy>`_.
