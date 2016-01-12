# cat.babu.fromemailaddresspermission

## From Email Address Permission

This extension allow to restrict sending emails using "Site From Email Address" to allowed user/roles.

The permission that enables this functionality is 'site from email address'.

**Important**

This extension overrides the following core 4.6.8/4.6.11 CiviCRM files:

- CRM/Contact/Form/Task/EmailCommon.php

- CRM/Core/BAO/Email.php

### Road Map

- Check all the core files where you can get from email address. Currently only has covered the most obvious. 

- It would be desirable if there were no way a user can send mail from addresses that were not his. So would prevent the user could change email addresses of CiviCRM users.