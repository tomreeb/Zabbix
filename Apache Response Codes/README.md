# Apache Response Codes
This Zabbix template uses Low Level Discovery rules to generate items to monitor Apache Status codes.

## How to use
Track different response codes by editing the array in `apache_respcode` script

### On the Apache Server
1) Copy the `apache_respcode` script to `/usr/local/bin` directory and make it executable
2) Add `apache_respcode.conf` to `/etc/zabbix/zabbix_agentd.d/` and restart the zabbix-agent service

### On Zabbix Server
1) Import the `apache_response_codes.xml` template and apply to your host
