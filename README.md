# cas-maestro
Custom version of the CAS Maestro WordPress plugin, including support for CAS attributes.

The changes so far are:
- Added support for using CAS attributes for name and email instead of LDAP 
- Added support for certificate validation (specify path to certificate or leave blank for no validation)
- Added option for specifying redirect URL (or leave blank for no redirect)
- Added option for specifying path to phpCAS library (or leave blank to load phpCAS from your PHP include path)
- Added option for specifying path to CAS debug log file (or leave blank to disable logging)
- Set password fields to only be removed from the profile page (but not from the 'Add New User' or 'Edit User' pages)
- Updated phpCAS to version 1.3.3

TODO:
- Add support for using CAS attributes for any profile field
- Add option for updating profile fields on every login, or just on account creation
