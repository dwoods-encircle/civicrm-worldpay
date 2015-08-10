This is a set of files to allow CiviCRM to use the WorldPay
payment gateway system. It is based upon code first
developed by Dougall Winship, expanded by Ian Macdonald, then further expanded by enCircle.

This STILL should be considered to be EXPERIMENTAL code which
should be extensively TESTED before being used in a
production environment.

TODOS:-

1) Accept future pay transactions from WorldPay!

PLEASE NOTE: A row needs to be added to the
civicrm_payment_processor_type table in order for CiviCRM
to register the existence of the WorldPay support. You
should either run the included addworldpayprocessor.php
script or manually add the apporopriate row to the database
in order for the payment gateway to be listed within the
CiviCRM interface.

The latest version of this code is currently available at
https://github.com/dwoods-encircle/civicrm-worldpay

Please email support@encircle.co.uk with any questions or contributions.

-The enCircle Team
www.encircle.co.uk
