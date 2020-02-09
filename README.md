# ZABBIX SERVER ROLE
With this ansible role you can install zabbix-server on a CentOS 8.1.
When the role finishes you can access the server using http://zabbix-ip-address/zabbix and finish the configuration
This role will install zabbix on Centos 8.1.

# IMPORTANT:
*This zabbix server is installed in a highly insecure manner. This is just for test. If you want to put this in production don't forget to change mysql root password and zabbix password.*
Mysql server is installed with blank password.
zabbix user and password are zabbix/zabbix
Web user/password: admin/zabbix

**This role is for test purposes, use it at your own risk**

# Copyright 
This application is licensed under GNU General Public License, Version 3.0 http://www.gnu.org/licenses/gpl-3.0-standalone.html