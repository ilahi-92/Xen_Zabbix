# Xen_Zabbix

Connect to VPN 

Connect to Jumpserver - RDP

zabbix server - x.x.x.x

zabbix proxy on which xen servera are configured

Create host in zabbix for xen server - 192.168.230.162
Attach template "linux by zabbix agent"

Once connected -

Xen Monitoring setup 

connecet to 192.168.230.162 from jump server 

Create 5 scritps

[root@clmu4c-ctx162 bin]# ls -ltrh
total 24K
-rwxr-xr-x 1 zabbix zabbix  428 Aug 29 13:26 xen_cpu_usage.sh
-rwxr-xr-x 1 zabbix zabbix 1.1K Aug 29 13:26 xen_info.sh
-rwxr-xr-x 1 zabbix zabbix  167 Aug 29 13:26 xen_used_memory.sh
-rwxr-xr-x 1 zabbix zabbix 1.5K Sep  2 12:28 xen_sr_utilization.sh
-rwxr-xr-x 1 zabbix zabbix 1.3K Sep  2 13:36 xen_vm_discovery.sh
[root@clmu4c-ctx162 bin]#

contents are attaached as files in repo






