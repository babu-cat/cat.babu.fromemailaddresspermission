# cat.babu.fromemailaddresspermission

## From Email Address Permission

This extension allow to restrict sending emails using "Site From Email Address" to allowed user/roles.

The permission that enables this functionality is 'site from email address'.

**Important**

This extension overrides the following core 4.7.22 CiviCRM files:

- CRM/Contact/Form/Task/EmailCommon.php
- CRM/Core/BAO/Email.php

### Road Map

- Check all the core files where you can get from email address. Currently only has covered the most obvious. 
- It would be desirable if there were no way a user can send mail from addresses that were not his. So would prevent the user could change email addresses of CiviCRM users.

### Related work and discussion

- [How to disable “From email address” for unauthorized users?](https://civicrm.stackexchange.com/questions/7236/how-to-disable-from-email-address-for-unauthorized-users)
- [CRM-5491 - ACL or Drupal permission to allow certain roles to choose between the "From email addresses"] (https://issues.civicrm.org/jira/browse/CRM-5491)