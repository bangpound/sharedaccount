Shared Accounts
---------------

This Drupal 7 module creates a new permission that controls whether a user can edit his own account.

Normally in Drupal, a user can it himself or --- if the user has `administer users` permission --- any user on the site. Users without this module's `edit own account` permission will not be able to change the account's password or email address.

This module ca be used to create shared accounts. When combined with [Content Access](http://drupal.org/project/content_access) and [LoginToboggan](http://drupal.org/project/logintoboggan), this allows site builders to create accounts that can access specific nodes with a password.

This module includes tests to verify that access to the user edit form is still secure.
