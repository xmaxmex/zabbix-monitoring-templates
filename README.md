zabbix-monitoring-templates

Steps in order to make it work:

Install ODBC drivers for your OS (Oracle)
Create some user in your Oracle database for Zabbix
Maintain your odbc.ini and add new DSN
 Fill corresponding connect DSN in {#DSN} and {#BACKUP_DSN} macro at your zabbix host.
Grant select any dictionary to created user at step #2.
If some specific permission is required for some specific item, it will be available at item description.

Future plans: 

Add more performance metric items and triggers
Add support for Oracle RAC
Add compatibility for Oracle DataGuard instances
